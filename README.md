
# Tic-Tac-Toe (Python)

This is a simple Tic-Tac-Toe game built using Python's Tkinter library for the graphical user interface (GUI). It allows two players to take turns and play the classic game. The game checks for win conditions (rows, columns, and diagonals) and also detects ties.

## Features

- Shows whose turn it is (Player X or Player O).
- Highlights the winning combination and declares the winner.
- Declares a tie if all spots are filled without a winner.
- Allows restarting the game at any point.



## How to Play
1. Player X starts the game.
2. Click on any of the 3x3 grid tiles to mark it with your symbol (X or O).
3. After each turn, the game will check if a player has won or if the game is a tie.
4. If a player has all their symbols in a row, column, or diagonal, they win.
5. The game will display the winner or declare a tie if all tiles are filled.
6. To restart the game, click the "restart" button.

## Prerequisites
- Python 3.x
- Tkinter (comes pre-installed with Python)

## Run Locally

Clone the project and run the Python file:

```bash
  git clone https://github.com/nk-rajkumar/Tic-Tac-Toe-Python/tree/main
```
Alternatively, download the project and run:

```bash 
python tic_tac_toe.py
```

The game window will open, and you can start playing immediately.


## Screenshots

![Screenshot (232)](https://github.com/user-attachments/assets/58d50581-1e07-4a4a-9dbd-960fbfb55d05)

![Screenshot (233)](https://github.com/user-attachments/assets/e724b0bc-bf8b-4e69-85b9-c363271e2f75)

![Screenshot (234)](https://github.com/user-attachments/assets/6a9bc2e8-8ab9-4d7a-bff1-e176128848f2)



## Code Explanation

Main functions

- set_tile(row, column): Handles the player’s move, updates the board, and switches turns.
- check_winner(): Checks if there’s a winner or tie after each move.
- new_game(): Resets the game board and starts a new game.


User Interface

- The game window is created using Tkinter’s Tk class.
- The game board consists of buttons arranged in a 3x3 grid.
- The game window always opens in the center of the screen for a better user experience.
- The game window is non-resizable, maintaining a fixed size throughout gameplay.

## Colour Reference

| Colour             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Colour_blue (player's tile) | #4584b6 |
| Colour_yellow (label and winner declaration) | #ffde57 |
| Colour_gray (frame background) | #343434 |
| Colour_light_gray (winning tiles background) | #646464 |
| Colour_white (label text) | #ffffff |

## Future Improvements

- Add sound effects when a player makes a move.
- Improve the user interface with animations.
- Add a single-player mode with an AI opponent.
- Add a score keeping for players and updating the score after every game.

## License

[MIT](https://choosealicense.com/licenses/mit/)

This project is licensed under the MIT License. Feel free to contribute or modify!

## Feedback

If you have any feedback, please reach out to me at:
📧 nkrajkumar02@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rajkumar-k-747984257/)
