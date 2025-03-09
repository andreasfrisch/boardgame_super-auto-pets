# Super Auto Pets -- a board game
Super Auto Pets is a board game for 2-4 players.
The game is played over a series of rounds where players draft cards to build a tableau.
The tableau is then used to compete in a combat phase where players gain victory points based on the power of their tableau.
Furthermore players can gain victory points by selling stacks of cards in their tableau during the game.

## Components
- 4 player boards
- 4 market refill tokens (one for each player)
- Victory point tokens (in values 1, 2, 3, 4, and 6)
- [X, To be determined] market cards
- Mosquito die
- Round tracker die
- Wound tokens
- These rules

## Setup
Shuffle all cards and deal 9 cards in a 3x3 grid in the center of the table. This is the market.
If playing with 4 players deal 12 cards in a 3x4 grid instead.
Each player receives a player board.
Place the victory point tokens in a pile next to the market.

Randomly determine the starting player.

## Round structure
The game is played over a series of rounds. Each round consists of the following phases:
- Market phase: Players take turns buying cards from the market.
- Combat phase: Players activate their tableau

### Market phase
In the beginning of each round, the market is refilled, by drawing cards from the deck until the market is full.

Starting with the first player and going clockwise, players take one card from the market.
This card is not replaced at this time.

Before taking a card, a player may choose to refill one row or column in the market.
To do this they remove all cards in that row or column and draw new cards from the deck to fill it up again.
Each player may only refill the market once per round -- use the market refill token for each player to keep track of this.

After selecting a card a player must place that card in their tableau.
If a player has no room left in their tableau they must discard a stack from their tableau or merge two cards in their tableau to make room.
A player may not discard the card they just picked up.
This is the only time a player may merge stacks or sell stacks in their tableau.

When placing a card in the tableau, the player may choose where that card goes.
The only rule is that the internal order of existing stacks must be maintained.

The players keep going around the table drafting cards until all players have drafted 5 cards.

If the market deck runs out of cards, shuffle the discard pile and create a new deck.
If the market runs out of cards, the player whose turn it is passes their turn.
If all player passes their turn, the round ends.
[Note: This can happen if no player elects to use their ability to refill the market or if the players choose to refill already full rows or columns]

Some cards have abilities that happen in the beginning of the market phase.
These abilities are resolved in player order, from rear to front, before the first player takes their first card.

#### Player Tableau
Each player has a tableau in front of them.
The tableau has 5 spaces for card stacks.
The leftmost space is called the 'rear' and the rightmost space is called the 'front'.
Players may leave empty spaces in their tableau.

The 5 spaces are also known as columns.
Some effects on cards affect columns and when this happens they affect that column on all player tableaus.

##### Selling stacks
When a player drafts a card, they may have to -- or choose to -- sell an existing stack to make room for the new card.
The player may sell a stack even if there is enough room to accomodate the new card.
When a stack is sold, the player gains victory points based on the level of the stack.
Players gain 1/3/6 victory points for selling a stack of level 1/2/3.

##### Merging stacks
If a player has multiple stacks of the same type, the player may merge those stacks into a single stack.
The new stack may have a maximum of 3 cards.
Any excess cards are discarded from the new stack, but if any cards are discarded this way, the player gains 1 victory point.

##### Upgrading stacks
When a player drafts a card of a type that is already in their tableau, they may choose to upgrade that stack.
This allows a player to draft a card even if there is no room for it in their tableau, without having to sell or merge other stacks first.

#### Card stacks
Cards in the tableau are placed in stacks.
A stack can contain up to three cards of the same type.
The amount of cards in a stack indicates the stacks level.

Most abilities have a different effect based on the level of the stack.
This is indicated as three values separated by slashes.
e.g. `2/4/6` means that the ability has a different effect at stack level 1, 2 and 3.

#### Card types
Cards come in two types; animals and food.
[Note: It is called food for historical reasons, but it is in effect upgrades]

An animal card can either take its own space in the player tableau or upgrade an existing card in the tableau if they are of the same type.
An animal which upgrades an existing card is tucked under the card it upgrades, sticking out slightly so that the type of the card is still visible.

A food card can only be picked up if there is a stack in the tableau.
A food can be applied to any stack and is placed below the stack as a reminder that the stack is affected by the food.
[Note: Chocolate works slightly differently and is not placed below the stack]

A stack can only have one food card below it at a time.
When drafting a food card, the player may choose to replace the existing food card with the new one.

Food cards do not affect the value of the stack when selling the stack.


### Combat phase
The combat phase comprises of two steps:
- Start of combat abilities
- Combat

#### Start of combat abilities
Some cards have abilities that happen at the start of the combat phase.
These abilities are resolved in player order, from rear to front.

Usually these abilities are used to wound other stacks.
In that case, place a wound token on the stack that is wounded as a reminder.
Wounded stacks become healthy again at the end of the round.

#### Combat
Each player adds up the power of their tableau.
Power is calculated from rear to front.
Wounded cards contributes no power, but they may still use their combat abilities.

The player with the most power gains 4 victory points and the player with the second most power gains 2 victory points.
The player with the least power becomes the first player for the next round.


## Victory
The game ends after a 6 rounds.
After the 6th round players can sell any remaining stacks in their tableau.
The player with the most victory points wins the game.



