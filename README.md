# Tic Tac Toe Game
A two player Tic Tac Toe game written in python, using Google Colab’s Jupyter Notebook.

## How to run
1. Open the notebook in Google Colab or Anaconda.
2. Run all.
3. The game starts in the last cell (main()). Type your answers in the box and press enter.

## How to play
- Two players share the keyboard. Player X always goes first, then player O.
- The board squares are numbered 1 to 9, as below.
```
     1 | 2 | 3
    ---+---+---
     4 | 5 | 6
    ---+---+---
     7 | 8 | 9
```
- On your turn, type the number of an empty square.
- Get three in a row (vertically, horizontally, or diagonally) to win.
- If all 9 squares are filled with no winer, it’s a draw.
- Type ‘q’ at any time to quit the game.

## Input checking
If the player types an invalid input, it will return a specific error message related to the issue, like:

- If the player types something that is not a number.
  - Output: That is not a number. Please enter a number from 1 to 9.

- If the player types a number that is not 1-9.
  - Output: That number is out of range. Please enter a number from 1 to 9.

- If the player picks a square that is already taken.
  - Output: That square is already taken. Please choose another one.

## Statistics
The game keeps track of games played, X wins, O wins, draws and the total number of moves across several games. They are shown after each game and when you finish playing. If a player quits the game, the statistics are not counted.
