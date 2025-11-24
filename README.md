Tic-Tac-Toe Game in Python

Step1. Introduction
---------------
This project is a simple and easy-to-understand Tic‑Tac‑Toe game made using Python.
It runs in the terminal and lets two players, X and O, take turns by entering positions.
from 1 to 9. The goal of this project was to practice basic Python concepts while creating
a small but complete working game. It uses simple logic, lists, and functions—making it
perfect for beginners.

Step2. How the Game Works
----------------------
- The game uses a list with 9 positions to represent the 3×3 board.
After each play, the board is printed so the players can view it.
- Players choose a number between 1 and 9 to place their symbol.
- If the chosen position is already occupied, the game prompts the player to try again.
- After every move, the program checks whether the current player has won.

- Turns are switched automatically between Player X and Player O.
- A match is drawn when the board has filled up and no one has won.

Step3. Winner's Logic
----------------
There are 8 possible ways to win:

- 3 rows

- 3 columns
- 2 diagonals
The player will win if he/she can fill any one of these lines with their symbol.

Step4. Running the Game
------------------------

1. Install Python, if it isn't already installed.

2. Save the script as: tic_tac_toe.py

3. Open your Command Prompt or Terminal.
4. To run the program, type:
python tic_tac_toe.py
5. Observe whatever is displayed on the screen.

Step5. What You Learn From This Project
---------------------------------

- How to hold and update game data using a Python list
- How to break code into smaller functions
- How loops and conditions create the flow of the game
- How to accept and validate player input
- How simple game logic is designed and implemented

Step6. File Structure
-----------------
project-folder/
│
├── tic_tac_toe.py

Step7. Conclusion
-----------------
This small project is great for anyone just starting with python. It teaches how a simple game is built from scratch using basic programming ideas. This game can later be enhanced by adding features such as a computer opponent, a graphical interface or even a scoring feature.

