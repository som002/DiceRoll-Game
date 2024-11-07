# Two-Player Dice Game

Website: (https://som002.github.io/DiceRoll-Game)

This is a simple two-player dice game where players take turns rolling dice, accumulating points, and trying to reach 100 points first. The game supports the following features:
- Rolling a dice to add points to the current score.
- Switching players when a 1 is rolled.
- Holding the current score and adding it to the total score.
- Declaring a winner when a player reaches 100 points.


## Introduction

This project is a simple implementation of a two-player dice game in JavaScript, HTML, and CSS. It includes features like rolling dice, holding scores, and switching turns. The game is played until one player reaches 100 points, at which point they win.



## How It Works

1. **Rolling the Dice**: When the player clicks the "Roll Dice" button, a random number between 1 and 6 is generated. If the player rolls a 1, their current score is reset to 0, and the turn switches to the other player. If the player rolls any other number, that number is added to the current score.

2. **Holding the Score**: When the player clicks the "Hold" button, the current score is added to the player's total score, and the turn switches to the other player.

3. **Winning the Game**: The first player to reach 100 points wins the game. When a player wins, their name will be highlighted as the winner.

## Game Features

- **Player Turns**: Players take turns rolling the dice and accumulating points.
- **Dice Rolls**: The dice roll result is displayed visually on the screen.
- **Score Display**: The current and total scores of each player are displayed.
- **Player Switching**: If a player rolls a 1, the turn switches automatically.
- **Game Reset**: A new game can be started by clicking the "New Game" button.

## Installation

To play the game locally:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/dice-game.git
2. how to start the game.
    ```bash
    Just double Click on index.html

followed tutorial of Jonas Schmedtmann
