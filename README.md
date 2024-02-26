Tic Tac Toe Game Documentation

Introduction

Tic Tac Toe is a classic two-player game played on a 3x3 grid. Players take turns marking spaces with their respective symbols (usually X and O) until one player achieves a winning pattern or the game ends in a draw.

Code Structure

The Tic Tac Toe game is implemented in Java with the following classes and methods:

Coordinates: Represents the coordinates of a move on the game board. It includes error handling for out-of-bounds moves.

OutBoundsMoveException: Custom exception class for out-of-bounds moves.

OccupiedCoordinateException: Custom exception class for occupied coordinates.

Main Class: Contains the main logic of the game, including methods for checking game status, processing user moves, and managing the game loop.

Methods for checking winning conditions such as rows, columns, and diagonals.

Methods for validating the game state, including checking for impossible states and draws.

Methods for processing user moves and handling user input errors.

Methods for printing the game board and displaying the game status.

The play() method orchestrates the game loop, allowing players to take turns until the game ends.

Gameplay Flow

Initialization: The game starts with an empty 3x3 grid.

Game Loop: Players take turns marking empty spaces on the grid until one player wins or the game ends in a draw.

Winning Condition: The game checks for winning patterns after each move, including horizontal, vertical, and diagonal lines of the same symbol.

Draw Condition: If no winning pattern is found and there are no empty spaces left, the game ends in a draw.

Error Handling: The game handles user input errors such as invalid coordinates and occupied spaces, prompting the player to make a valid move.

Game Status: After each move, the game prints the updated board and displays the current game status, indicating whether the game is ongoing, won by a player, or ended in a draw.

Running the Game

To play the Tic Tac Toe game, run the Main class. Follow the prompts to input the coordinates of your moves. Players take turns marking empty spaces with their symbols (X or O) until one player wins or the game ends in a draw.

Conclusion

The Tic Tac Toe game provides a simple yet engaging experience for players of all ages. With its intuitive gameplay and strategic depth, it remains a timeless classic in the world of board games. Whether playing against a friend or challenging the computer, Tic Tac Toe offers endless entertainment and opportunities for strategic thinking.
