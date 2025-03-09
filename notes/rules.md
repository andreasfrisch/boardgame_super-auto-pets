# Setup
Shuffle all cards and deal 9 cards in a 3x3 grid in the center of the table. This is the market.
Each player receives a player board.
Place the victory point tokens in a pile next to the market.

Randomly determine the starting player.

# Round structure
The game is played over a series of rounds. Each round consists of the following phases:
- Market phase: Players take turns buying cards from the market.
- Combat phase: Players activate their tableau

## Market phase
Starting with the starting player and going clockwise, players take one card from the market.
This card is not replaced.

Before taking a card, a player may choose to refill one row or column in the market.
To do this they remove all cards in that row or column and draw new cards from the deck to fill it up again.
Each player mau only refill the market once per round.

After selecting a card a player must place that card in their tableau.
If a player has no room left in their tableau they must discard a stack from their tableau or merge two cards in their tableau to make room.
[?] A player may not discard the card they just picked up.

When placing a card in the tableau, the player may choose where that card goes.
The only rule is that the internal order of existing stacks must be maintained.

During the market phase each player will draft 3 cards one at a time.

Some cards have abilities that happen in the beginning of the market phase.
These abilities are resolved in player order, from rear to front, before the first player takes their first card.

### Player Tableau
Each player has a tableau in front of them.
The tableau has 5 spaces for card stacks.
The leftmost space is called the 'rear' and the rightmost space is called the 'front'.
Players may leave empty spaces in their tableau.

#### Selling stacks
When a player draft a card, they may have to -- or choose to -- sell an existing stack to make room for the new card.
The player may sell a stack even if there is enough room to accomodate the new card.
When a stack is sold, the player gains victory points based on the level of the stack.
Players gain 1/3/6 victory points for selling a stack of level 1/2/3.

#### Merging stacks
If a player has multiple stacks of the same type, the player may merge those stacks into a single stack.
The new stack may have a maximum of 3 cards.
Any excess cards are discarded from the new stack, but if any cards are discarded this way, the player gains 1 victory point.

### Card stacks
Cards in the tableau are placed in stacks.
A stack can contain up to three cards of the same type.
The amount of cards in a stack indicates the stacks level.

Most abilities have a different effect based on the level of the stack.
This is indicated as three values separated by slashes.
e.g. `2/4/6` means that the ability has a different effect at stack level 1, 2 and 3.

### Card types
Cards come in two types; animals and upgrades.

An animal card can either take its own space in the player tableau or upgrade an existing card in the tableau if they are of the same type.
An animal which upgrades an existing card is tucked under the card it upgrades, sticking out slightly so that the type of the card is still visible.

An upgrade card can only be picked up if there is a card in the tableau that it can upgrade.
An upgrade can upgrade any animal that does not already have an upgrade.


## Combat phase
The combat phase comprises of two steps:
- Start of combat abilities
- Combat


### Start of combat abilities
Some cards have abilities that happen at the start of the combat phase.
These abilities are resolved in player order, from rear to front.

### Combat
Each player adds up the power of their tableau.
Power is calculated from rear to front.

The player with the most power gains 4 victory points and the player with the second most power gains 2 victory points.
The player with the least power becomes the starting player for the next round.


# Victory
The game ends after a 10 rounds.
After the 10th round players can sell any remaining stacks in their tableau.
The player with the most victory points wins the game.



