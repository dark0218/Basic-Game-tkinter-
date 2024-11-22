Tic Tac Toe Game in Python

 Overview

This is a GUI-based Tic Tac Toe game built with the use of Python's tkinter module. It allows two players to compete on a simple 3x3 grid format aiming for three marks at least in a straight line horizontally, vertically, or diagonally.

Features
Two-Player Mode
The players make turns marking the grid with either X or O.
Win Detection
The program automatically identifies and displays the winner upon three marks becoming aligned.

Tie Condition
If the grid is filled and no player wins, then the game declares a tie.

Interactive GUI
Buttons and labels make the game highly interactive with a clean, non-cluttered interface.

Player Names
Players can input their names for a more personalized experience.

How to Play
Start the Game
Run the script to launch the Tic Tac Toe game window.

Input Player Names

In the "Player 1" field, enter Player 1's name and in the "Player 2" field, Player 2's name.

Make Moves
The players take turns clicking on open grid buttons to place their mark. X is Player 1, and O is Player 2.

Win or Tie

The game declares the winner as soon as a player places three marks.
If there is no winner and the grid is full, the game declares a tie.
How to Run the Code
Requirements

Python 3.x installed on your system.
No external libraries necessary, uses the built-in tkinter module.


 Execution

Save the script as a file with a .py extension, for example, tic_tac_toe.py and execute it using:


python tic_tac_toe.py


Game Rules

The grid is 9 cells wide, in a 3x3 grid.
Players take turn, beginning with Player 1 (X).
A player wins if they align three of their marks (X or O) in:
A row (horizontal)
Column (vertical)
Diagonal (either left-to-right or right-to-left)
If all the cells are occupied without a winner, then game results in a tie.


Preview


Player Name Input Fields: Enable players to input their names
Game Board: Interactive buttons for the player to place X's and O's.
Alerts: Pop-up messages that notify of any win, tie, or invalid move.


Future Enhancements

Add a restart button that allows replaying without closing the game
Provide an option to choose who plays first
Include an AI opponent for the single-player mode.
Have fun playing Tic Tac Toe! ????

