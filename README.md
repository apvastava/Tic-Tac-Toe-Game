# Tic-Tac-Toe Game

This is a simple implementation of the Tic-Tac-Toe game in Python. The game is played on a 3x3 grid where two players take turns marking a cell in the grid with their respective symbols ("X" and "O"). The first player to get three of their symbols in a row, column, or diagonal wins the game. If the grid is filled without any player achieving this, the game ends in a draw.

## Functions

### `print_board(board)`
Prints the current state of the board.

- **Parameters**: 
  - `board`: A 2D list representing the Tic-Tac-Toe board.

### `check_winner(board, player)`
Checks if the specified player has won the game.

- **Parameters**: 
  - `board`: A 2D list representing the Tic-Tac-Toe board.
  - `player`: A string representing the player ("X" or "O").

- **Returns**: 
  - `True` if the player has won, `False` otherwise.

### `is_board_full(board)`
Checks if the board is full.

- **Parameters**: 
  - `board`: A 2D list representing the Tic-Tac-Toe board.

- **Returns**: 
  - `True` if the board is full, `False` otherwise.

### `play_game()`
Main function to play the game. Handles the game loop and player inputs.

## How to Play

1. Run the `play_game()` function to start the game.
2. Players will be prompted to enter the row and column where they want to place their symbol.
3. The game will continue until one player wins or the board is full (resulting in a draw).
