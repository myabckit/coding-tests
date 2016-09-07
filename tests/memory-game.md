# Memory game

Create an online memory game. A list of cards with images or symbols in their
back will be displayed to the user. The user has to flip them over in pairs,
trying to create matches between the images/symbol in each revealed card.

## Use cases

1. A list of random cards is displayed to the user.

    1. The amount of cards will be always an even number.

    2. The order the cards are displayed must be random.

    3. Every card has two faces: a front/visible face and a back/hidden one.

    4. All front sides are indistinguishable from each other.

    5. Back card sides contain one image or symbol.

    6. The image/symbol in the hidden side must be present in two of the cards.

2. The game is played by turns. Every turn, the player flips two of the cards.

3. If the images/symbols in the revealed cards are the same, the remain revealed the rest of the game.

4. If they are different, the cards are flipped again, hidding the revealed images.

5. The game finishes when all cards have been revealed. The game starts again in use case #1.

## Requirements

- Use [ember](http://emberjs.com) and [ember data](https://github.com/emberjs/data) to code the main front-end app.
- The app must work in modern mobile browsers.

## Bonus points

- Use an API to store the game state.
- Add a test suite.
- Sound effects.
- New game mechanics.

