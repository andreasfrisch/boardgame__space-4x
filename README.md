# 4X Space Euro

Space-themed 4X game with a euro flair.

The <XYZ> entry for my 2019 Boardgame Prototype Challenge (https://gist.github.com/andreasfrisch/74fc8bc0fe5b34672c1f5d8dae21f3e7)

## What you need

* A printout of the cards in this repository.
* A printout of the game board in this repository.
* A printout of the outer rim anomalies.
* Goods cubes in three different colours. 
* Miniatures representing outposts, warships and transports in different player colours.
* An assortment of coins.

## Setup

* Place the game board in the middle of the table
* Place a shuffle token on the shuffle track
* Place the goods cubes and coins nearby
* Give each player a deck of action cards and all tokens in the same colour
* Each player also receives 5 credit
* Shuffle the outer rim planets, and place one on each outer rim space. Return the rest to the box.
* Determine which quadrant is not part of the game. There should be 1 quadrant per player.
* Put one goods cube of each type on the market track for each quadrant on the indicated space.
* Determine a starting player.
* Each player now shuffles their decks and draw 5 cards

## Anatomy of a card
Each card in a player deck will have one or two actions on them.
During a player's turn, they will play cards from their hand to perform the given action.

Some cards will have a lightning symbol and be marked as tactics.
Tactics can only be used at certain points in time, as described on the tactics themselves.

If a card has multiple actions printed on it, only one can be used when that card is played.

### Player Deck Card Count
The player decks consists of 20 cards initially.
The cards can be found in the \it{player_deck_cards.pdf}.

## Player Pieces
Besides their action deck players will have the following pieces:

* 8 Outpost tokens, of which 1 is used as a shuffle marker
* 4 Trade Ships
* 4 Warships
* 2 Scout Ships
* 8 Settlers

These elements are meant to be limited in number.

## Taking your turn
On a players turn they will play cards from their hand in order to take actions.
The actions available are determined by the cards.
Most cards will allow players to pay credit or discard other cards in order to improve the effect.
A player does not have to spent all the cards in their hand if they do not want to.
At the end of a player's turn, they draw back up to 5 cards.

If a player has run out of cards in their deck, they shuffle all their used cards to form a new deck.
If the player was owed any cards, they continue drawing from this newly shuffled pile.
Whenever a player shuffles their deck, move their shuffle token forward 1 space on the shuffle track on the board.

## Terms

### Fleet
A fleet is a group of ships belonging to the same player.
When asked to select a fleet, a player may select any number of ships on the same space -- not necessarily all of them.

### Card Actions

#### Move
Allows player to discard cards for movement points, moving a single fleet.
Playing a movement card in itself gives no movement points
Movement between sectors (from planets of one colour to planets of another colour), costs one additional movement point.
Players may pick up and drop off ships during movement.
Moving into the Outer Rim immediately reveals the anomaly there.
Players may not continue moving after revealing a planet.
In case players reveal a wormhole, they immediately move to the other wormhole if present.
Players may not leave a space if there are more enemy warships than friendly warships on that space -- unless permitted by the controlling opponent.
Scout ships add +1 Movement point to a fleet.

NOTE: players may give money to other players.

##### Outer Rim Anomalies (10)
* 2 Wormholes
* 2 Alien with power 3
* 3 Smuggler Cave (1 in each colour)
* 2 Empty
* Black Market (buys as central planet)

#### Produce
Produce resources at a planet you have an outpost (up to population)
Planets can only produce if they have a production specialty.
Planets only produce goods of their specialty.
Goods cost 1 card / coin per good produced.
Players don’t have to produce all possible goods if they don’t want to.

NOTE:
Loading ships:
Ships on planets may, as a free action, load cubes from that planet on board.
If the player has an outpost on the planet, this is free
If not, the player must pay 1 coin to any player with an outpost there
Players cannot load ships if there are more enemy warships on that planet, than friendly warships

* Warships may have 0 goods
* Scout ships may have 1 goods
* Trade ships may have 3 goods

#### Sell
Trade: Discard one card for each planet you want to trade on
Sell resources from a ship at a planet (no enemy fleet present, and not of a goods type the planet specializes in)
Look at the current value for the goods sold in the current sector.
Gain that amount of credit per good sold.
Then reduce the market track for the goods sold, for that sector, for each good of that type sold.
Players cannot sell resources on a planet, if there are more enemy warships on that planet, than friendly warships.
Players may only sell as many resources as there are population + settlers on the planet.

All other markets raise their perceived values of the sold goods type by 1.

#### Research
Play to start researching a technology tile.
A single technology tile costs 4 cars/credit and a double tile costs 10

The player will receive the tile when next shuffling his deck.
The player then immediately slots the tile into his research board.

When activating the abilities shown in the research board, go down through the board and get all the benefits listed there.

#### Build
Build ships at an outpost (up to population)
Ships cost 2 cards/credits each

#### Establish Outpost
Pay 1 card/credit per planet you want to outpost.
There are two ways to establish an outpost: Through trade or through military might.

In either case, you must add a Bureaucracy card to your discard pile.

##### Establish Through Trade
Pay goods to add Outpost to a planet where you have a ship (resources equal to population and of a type not produced by the planet)
If you have settlers on a planet without having an outpost, you may take the opponents outpost for free unless:

* The opponent also have settlers on the planet

OR

* The opponent has a warship on the planet

##### Establish Through Military Might
If you have a military strength (warships + settlers) equal to the planets defense (population + opponent settlers) you may establish an outpost on the planet.
Reduce the planets population by 1 and remove all enemy settlers.

NOTE: You may attempt to establish an outpost through military might, knowing you will fail, simply to reduce the population of the planet.

####  Colonize
Add population to a planet with an outpost you control.
Adding population costs X cards/credits where X is the amount of population + settlers on the planet already.

#### Engage:
Allows players to engage.
Player may start X engagements (where X is the additional card/credits spent).
For each engagement select a planet to either attack an outpost there or attack a fleet there.

##### Attack Outpost
Attacker must have 1 offensive power (warships + settlers) to declare this engagement.
If the attacker match the defense of the planet (enemy warships + population + enemy settlers + 1 for the outpost):
Remove enemy settlers, and replace enemy outpost with their own.
If the attacker does not win, destroy all the attackers settlers.
In any case, reduce population by one.

NOTES:
Whenever a player loses an outpost, they may remove a Bureaucracy card from their deck.
Whenever a player gains an outpost, they must add a Bureaucracy card to their discard pile.

##### Attack Fleet
Attacker must have at least 1 warship.
Add up total attack strength for each side (number of warships).
The player with the least strength loses half their ships rounded up.
The attacker loses 1 ship if the defender has at least one attack strength
Then, if both sides decide to stop attacking, the engagement is over.
If both players are still present, and cannot agree to stop fighting, again determine strengths and remove ships.

Notes:
Attacks can only be done by playing aggression cards.
Multiple fleets can share a space ‘peacefully' until one player triggers a conflict.
As with movement; Players may give money to other players as bribe/incentive to stop.

### Card Tactics

#### Hidden Weapons
Play at any time:
Your scouts counts as warships for the rest of the current player's turn.

#### Decoy Fleet
Play during space battle:
As loser: Remove one scout ship from the engagement, ignore all other losses for this battle round.
As winner: ignore ship loss for this battle round

#### Swift Manoeuvres
Play at any time: Immediately perform a move as if you had just played a single Move Action card. This move ignore enemy blockades.
You still have to pay cards or credit to generate movement points.

#### Local sympathisers
Play during a ground battle:
If attacker: The defender cannot count the local population as Battle Strength.
If defender: Get +2 Battle Strength from population, but if losing, reduce population by 1 additional point.

## End of the game
The game will end in one of three different ways:

* Whenever a player has reached the end of the shuffle track, this indicates the end of the game.
* Whenever a player places an outpost on the central planet.
* Whenever a player places their last outpost on the board.

When either of these are triggered, complete the current round, so that all players had an equal amount of turns.
Then calculate the final score.

## Scoring
Score is calculated as follows:

* Each credit is 1 point
* Each outpost is 2 points
* Each settler is 2 points
* Controlling the central planet is 4 points
