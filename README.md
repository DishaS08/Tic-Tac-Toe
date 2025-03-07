Tic-Tac-Toe (Python CLI Game)
Overview
This is a command-line Tic-Tac-Toe game where two players take turns placing "X" and "O" on a 3×3 board. The game checks for victory conditions, prevents moves on occupied spaces, and declares a draw if the 
board fills up without a winner.

Features
✅ Two-player gameplay
✅ Detects wins and draws
✅ Ensures valid moves
✅ Simple and interactive CLI-based game

How to Play
Players take turns entering a position (1-9) to place their mark.
The board updates after each move.
The game announces the winner when a player gets three marks in a row, column, or diagonal.
If all spaces are filled without a winner, the game ends in a draw.


Example Gameplay
arduino

|   |   |   |
|   |   |   |
|   |   |   |

Your turn player 1
Enter your move (1-9): 5

|   |   |   |
|   | X |   |
|   |   |   |


Run the Game
To play, save the script as tic_tac_toe.py and run:

bash
python tic_tac_toe.py


Requirements
Python 3.x


Future Enhancements
Add AI opponent
Implement a GUI version
