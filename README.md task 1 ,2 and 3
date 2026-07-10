# Tic-Tac-Toe AI (Minimax Algorithm)

A simple command-line Tic-Tac-Toe game written in Python where you play against an AI that uses the **Minimax algorithm** to make optimal moves.

## Features

- Play against an unbeatable AI.
- AI uses the Minimax algorithm.
- Input validation for player moves.
- Detects wins, losses, and draws.
- Simple command-line interface.

## Requirements

- Python 3.x

No external libraries are required. The project only uses Python's built-in `math` module.

## Project Structure

```
tic_tac_toe.py
README.md
```

## How to Run

1. Clone or download this repository.

2. Open a terminal in the project folder.

3. Run the program:

```bash
python tic_tac_toe.py
```

## Board Layout

The board positions are numbered as follows:

```
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9
```

Enter the corresponding number to place your **X**.

## Gameplay

- You play as **X**.
- The AI plays as **O**.
- The player always moves first.
- The AI automatically calculates the best possible move using the Minimax algorithm.
- The game ends when:
  - A player wins.
  - The AI wins.
  - The board is full (Draw).

## Example

```
Board positions:
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9

  |   |
---------
  |   |
---------
  |   |

Enter position (1-9): 5

  |   |
---------
  | X |
---------
  |   |

AI makes its move...

O |   |
---------
  | X |
---------
  |   |
```

## Minimax Algorithm

The AI uses the **Minimax algorithm**, a recursive decision-making algorithm commonly used in two-player games.

### Scoring

- AI wins → **+1**
- Player wins → **-1**
- Draw → **0**

The algorithm explores every possible game state and chooses the move with the highest score, making the AI impossible to beat if implemented correctly.

## Functions

| Function | Description |
|----------|-------------|
| `print_board()` | Displays the game board. |
| `check_winner(player)` | Checks whether a player has won. |
| `is_draw()` | Checks if the game is a draw. |
| `minimax()` | Calculates the optimal move score. |
| `ai_move()` | Executes the AI's best move. |
| `player_move()` | Accepts and validates player input. |
| `print_positions()` | Displays board position numbers. |
| `play()` | Controls the game loop. |

## Future Improvements

- Add difficulty levels (Easy, Medium, Hard)
- Alpha-Beta Pruning for optimization
- GUI using Tkinter or Pygame
- Scoreboard
- Restart game option
- Randomized opening moves
- Multiplayer mode

## License

This project is open source and free to use for learning and educational purposes.
