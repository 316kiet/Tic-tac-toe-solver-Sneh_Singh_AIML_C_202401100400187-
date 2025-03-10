# Tic-Tac-Toe with Minimax AI

## Description

This is a simple command-line implementation of the classic Tic-Tac-Toe game, where the player competes against an AI opponent. The AI uses the Minimax algorithm to make optimal moves, ensuring a challenging gameplay experience.

## Features

- A 3x3 Tic-Tac-Toe board
- Player (`O`) vs. AI (`X`)
- AI uses the Minimax algorithm for optimal decision-making
- Input validation to prevent invalid moves
- Automatic game status detection (win, lose, or draw)

## How to Play

1. Run the script in a Python environment.
2. The player (`O`) makes the first move by entering the row and column (0-2) separated by a space.
3. The AI (`X`) will then make its move automatically.
4. The game continues until there is a winner or the board is full (resulting in a draw).
5. The result of the game is displayed at the end.

## Installation & Usage

1. Ensure you have Python installed (version 3.x recommended).
2. Download or clone this repository.
3. Run the script using the command:
   ```sh
   python tic_tac_toe.py
   ```
4. Follow the on-screen prompts to play.

## Example Gameplay

```
Welcome to Tic-Tac-Toe!
You are O and the computer is X.
Let's start!

  |   |  
---------
  |   |  
---------
  |   |  

Enter your move (row and column from 0 to 2): 1 1

Your move:
  |   |  
---------
  | O |  
---------
  |   |  

Computer's move:
  |   |  
---------
  | O | X
---------
  |   |  
```

## Code Structure

- `check_winner(board)`: Checks for a winner or a draw.
- `evaluate(board)`: Evaluates the board state for the Minimax algorithm.
- `minimax(board, depth, is_maximizing_player)`: Implements the Minimax algorithm.
- `find_best_move(board)`: Finds the best move for the AI.
- `print_board(board)`: Prints the current state of the board.
- `is_valid_move(board, row, col)`: Checks if a move is valid.
- `play_game()`: Handles the game loop and user interaction.

## License

This project is licensed under the MIT License - feel free to modify and distribute.

## Author

Sneh singh

