# Tic-Tac-Toe (Java)

A command-line Tic-Tac-Toe game implemented in Java for two players (X and O). Features a 3x3 grid, input validation, win/tie detection, and a clean, object-oriented design.

## Features
- Two-player gameplay (X and O).
- Input validation for row/column (0-2) and occupied cells.
- Checks for wins (rows, columns, diagonals) and ties.
- Clear console-based board display.
- Error handling for non-numeric inputs.

## Prerequisites
- Java Development Kit (JDK) 8 or higher.
- A terminal or IDE (e.g.,VSCode, IntelliJ, Eclipse).

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/shivrajcodez/tic-tac-toe-java.git
   cd tic-tac-toe-java
   ```
2. Compile the Java file:
```bash
javac TicTacToe.java
```

3. Run the game:
```bash
java TicTacToe
```

## How to Play
- The game starts with an empty 3x3 grid.
- Players take turns entering a row (0-2) and column (0-2) to place their mark (X or O).
- The game checks for a winner or tie after each move.
- The board is displayed after each turn, and the game ends with a win or tie message.

## Example
```bash
Welcome to Tic-Tac-Toe! Enter row (0-2) and column (0-2) to play.
  |   |  
---------
  |   |  
---------
  |   |  
Player X, enter row: 
1
Player X, enter column: 
1
  |   |  
---------
  | X |  
---------
  |   |  
...
```
