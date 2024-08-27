#Tic-Tac-Toe Game
This is a simple console-based implementation of the classic Tic-Tac-Toe game. The project is written in Python and is designed to be easy to understand and extend. It features a player-vs-player mode, where two players take turns playing against each other and includes menus to start, end, or restart the game.

##Features
-Two-player gameplay: Two players can play against each other.
-Simple UI: The game is displayed on the console with a grid representing the board.
-Menu system: Includes options to start a new game or quit.
-Input validation: Ensures that players enter valid names, symbols, and board positions.
-Win/draw detection: Automatically detects when a player wins or when the game ends in a draw.
-Replayable: After the game ends, players have the option to start a new game or quit.
##Requirements
Python 3.x
##How to Run
-Clone the repository:
--git clone https://github.com/your-username/tic-tac-toe.git
-Navigate to the project directory:
--cd tic-tac-toe
-Run the game:
--python tic_tac_toe.py
-Follow the on-screen instructions to play the game.

##How to Play
1.Upon starting the game, you will be prompted to enter player names and their respective symbols (a single letter).
2.Players take turns choosing a position on the board by entering the number of the cell they wish to place their symbol in.
3.The game will announce the winner if a player successfully lines up three of their symbols in a row, column, or diagonal.
4.If all cells are filled and no player has won, the game will declare a draw.
5.Players can choose to start a new game or quit after each match.

##Project Structure
tic-tac-toe/
├── tic_tac_toe.py   # Main game code
└── README.md        # Project documentation
