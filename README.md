# Blackjack Game

## Overview

Welcome to the Blackjack Game! This simple web application lets you enjoy the classic game of Blackjack, where the goal is to get as close to 21 as possible without exceeding it. Let's analyze the code and understand how to play.

## Project Structure

- `index.html`: HTML structure for the game.
- `blackjack.css`: CSS styling for a visually appealing interface.
- `blackjack.js`: JavaScript code for game logic and functionality.

## How to Play

1. Click the "New Game" button to start a new round.
2. Each Round will cost $10.
3. You will be dealt two cards, and the sum of their values will be displayed.
4. Draw additional cards ("New Card" button) to get closer to 21 without exceeding it.
5. If your sum is 21, you win the round and earn $30 to your balance.
6. If your sum exceeds 21, the game is over, and you lose the $10 of the round from your balance.
7. You start each round with $100, and the goal is to maximize your balance.

## User Interface

- Dark green background and goldenrod text color for an appealing visual experience.
- Responsive buttons with hover effects for a user-friendly interface.
- Display of current sum, cards, result, and player balance.

## Game Logic

- The game uses a simple deck of cards with values ranging from 1 to 13.
- Face cards (11, 12, 13) are represented as J, Q, K, respectively.
- Ace (1) is represented as A.
- Each round costs $10, and winning a round adds $30 to the player's balance.

## Important Notes

- The game dynamically updates the UI to show the current sum, cards drawn, and the result of each round.
- The player starts with $100 and continues playing until they run out of credits.
- Once credits are exhausted, the "New Game" button is disabled, and the game informs the player that all credits are over.

## Acknowledgments

Special thanks to [FreeCodeCamp](https://www.freecodecamp.org/) for providing valuable learning resources and a supportive community. The knowledge gained from FreeCodeCamp's tutorials and projects has greatly contributed to the development of this Blackjack Game.

## Getting Started

1. Clone this repository to your local machine.
2. Open the `index.html` file in your preferred web browser.
3. Start playing Blackjack and aim to maximize your balance!

Feel free to reach out->[LinkedIn](https://www.linkedin.com/in/aakarsh-arora-b3965822b/) if you have any questions or feedback. Enjoy the game! 🃏💰
