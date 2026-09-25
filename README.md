# 3D-ChessBot
A simple command-line 3D chess game written in Python. Instead of playing on a traditional 2D chessboard, the game represents the board as an N × N × N matrix, allowing pieces to exist and move in three dimensions.
The player can play against a very simple computer-controlled opponent. The bot has essentially no strategic intelligence—it simply selects a random valid move from the available moves.
There is no graphical user interface. The board, game state, and all other output are displayed directly in the command line, and the player enters their moves through command-line input.

# Requirements and Dependencies
Python 3.10+
No external Python packages are required for the basic version of the game.

You can check your installed Python version with:
python --version

# Installation Instructions
Simply download the repository and run "3d-chess.py" in any command-line interface with 
```python
python 3d-chess.py
```

# Usage Instructions
After starting the program, the game will display the current 3D board in the command line and prompt the player to enter a move.
The player enters moves in the form **(x,y,z) -> (x,y,z)** where x is the horizontal position on the board, y is the vertical position, and z is the chosen board in the 3D space.
The bot will then have the opportunity to move and then the new board state will be displayed to the player. This will continue until either the player or the bot wins, or the player enters "ff" to forfeit.

# Project Status
This project is still in the early development stage and is not available for playtesting yet. 
This repository will be updated with the latest game builds as they are developed

# Project Roadmap
1. Create a text file containing all possible movements for each chess piece to aid in development
2. Create a simple function to display the current board on a command line
3. Implement chess pieces and test each one's valid movements
4. Create a simple bot that will observe all valid moves and take an enemy piece if possible, choose random valid move otherwise
5. Playtest functionality
6. Implement an actual User Interface to facilitate gameplay

# Contributing
Contributions are welcomed and encouraged! If you want to contribute, feel free to fork the repository and create your own branch.
Pull requests will receive a response within 2 weeks of submitting.

### Contribution Instructions
1. Fork the repository.
2. Create a new branch.
    ```git checkout -b feature/my-new-feature```
3. Make your changes.
4. Commit your changes.
    ```git commit -m "Add my new feature"```
5. Push the branch.
    ```git push origin feature/my-new-feature```
6. Open a pull request on GitHub.

# Contact Information
Please send any questions or concerns to jcd288@nau.edu.
I will try to answer any questions within 48 hours of receiving them.
