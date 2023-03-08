# Catan

The project is to implement computer version of Catan board game.

## Main rules

Further information: https://www.catan.com/sites/default/files/2021-06/catan_base_rules_2020_200707.pdf


- Game is suitable for 3-4 players
- The players take on the role of settlers establishing settlements in the Island of Catan, they build settlements, cities and roads to be connected as they settle the island.
- The game board is composed of hexagonal tiles (hexes), laid out randomly at the beginning of the game.
- Players build spending resources (wool, grain, lumber, brick and ore) decipted using resource cards;  hills produce brick, forests produce lumber, mountains produce ore, fields produce grain, and pastures produce wool.

### Rolling the dice
-
- Each player's turn starts with the rolling of two six-sized dice, this is used to determined which hexes produce resources.
- Those who have a settlement adjacent to a hex with the number visible in the dice, receive a card of the corresponding resource.
- Those who have a city adjacent to a hex with the number visible in the dice, receive two cards of the corresponding resource.
- A robber token is initially placed in the desert.
- If the number on the dice is 7, then the robber is activated
    - If anybody has more than 7 card, they need to give away half of them (chosen ones)
    e.g. if you have 8 you have to give away 4, however if you have 9 you should give away also 4 cards
    - The person, who rolled the dice, can block one of the resource fields,
    and then they steal one card from one of the people, who are next to the blocked filed
    - The thief stays on the field

### Trading

- As another possible action that can be taken in-game, players can trade with other players or with the bank
- Anybody then can make an offer to trade (but only with this player)
- As a default trading with bank is 4 similar resources for chosen one
    - e.g. 4 woods for 1 wheat
    - when you have a harbour, then trading with bank can be 3:1 or 2:1

### Building

- After trading, it’s time to build (if there are enough resources)
- From resources you can buy village, city, road or development card
    - ********************village -******************** gives 1 resources when number is on the dice
    - **************city -************** gives 2 resources, when number is on the dice, can be built only on the village (exchange)
    - ************road -************ connects villages/cities, because village can be built only if is connected to another village/city
    - **************************************develompment card -************************************** gives extra points, resources or knight, who can move the thief

## Multiplayer implementation

- Firstly, we will implement a game, that allows playing woth other people locally on one computer
- Eventually, if there is enough time and human resources, we will extend it to playing on the internet

## Technology used (expected)

- Java - for backend, game’s logic
- Javascript with frameworks - for frontend, interface
- MongoDB - database used to save users’ profiles
- Coding style: [https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)

## Team:

- Norberto Farias Cassinello
- Antonio Maña
- Minerva Gomez
- Pablo Ferreiro
- Pablo Luis Molina Blanes
- Emilio Rodrigo Carreira Villalta
- Zuzanna Furtak
- Agnieszka Lasek
- Ivan Iroslavov Petkov

## Citations:

Wikipedia contributors. (2023, January 16). Catan. In Wikipedia, The Free Encyclopedia. Retrieved 12:18, March 8, 2023, from https://en.wikipedia.org/w/index.php?title=Catan&oldid=1133942167
