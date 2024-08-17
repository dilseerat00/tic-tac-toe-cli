# Tic-Tac-Toe Game in Python

This repository contains a Python implementation of the classic Tic-Tac-Toe game, where the user plays against the computer. The computer makes the first move, and the user plays by entering numbers corresponding to the positions on the grid.

## Features

- **Computer vs. User:** The game is played between the computer and the user, with the computer always making the first move.
- **Simple Input Method:** The user selects their move by entering a number from 1 to 9, which corresponds to a position on the 3x3 grid.
- **Intelligent Moves:** The computer's moves are predetermined or can be made more intelligent based on a simple algorithm.
- **Winning Conditions:** The game checks for a winner after each move, considering all possible win conditions (rows, columns, diagonals).
- **Draw Detection:** The game detects and announces a draw if the grid is completely filled without a winner.
- **Replay Option:** After the game ends, the user can choose to play again or exit.

## How to Play

1. **Run the Script:** Start the game by running the Python script.
2. **Computer's Move:** The computer will automatically make the first move.
3. **User's Move:** The user will be prompted to enter a number from 1 to 9 to place their mark (O) on the grid. The numbers correspond to positions as follows:
4. **Game Progression:** The game alternates between the computer's and user's moves until there is a winner or the game ends in a draw.
5. **Result Announcement:** The game will announce the winner or if the game ends in a draw.
6. **Play Again:** After the game ends, the user can choose to start a new game or exit.

## Example Run
Computer's turn: X
1 | 2 | X
---------
4 | 5 | 6
---------
7 | 8 | 9

Your turn (O). Enter a number (1-9): 5

1 | 2 | X
---------
4 | O | 6
---------
7 | 8 | 9

Computer's turn: X
1 | 2 | X
---------
4 | O | X
---------
7 | 8 | 9

Your turn (O). Enter a number (1-9): 9

1 | 2 | X
---------
4 | O | X
---------
7 | 8 | O



