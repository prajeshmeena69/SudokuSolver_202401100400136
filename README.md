# SudokuSolver_202401100400136

# Sudoku Solver Game

## 📌 Introduction
This is a Python-based **Sudoku Solver Game** that allows users to either manually solve a Sudoku puzzle or use an **automated solver** based on the **backtracking algorithm**. The game ensures correct placement of numbers while following Sudoku rules.

## 🔧 Features
- **Generate Sudoku Puzzle** with random pre-filled numbers.
- **User Input Support** to manually solve the puzzle.
- **Move Validation** to ensure correct placements.
- **Automatic Solver** using the backtracking algorithm.
- **Formatted Board Display** for better readability.

## 🛠️ How It Works
1. The game generates a **9×9 Sudoku grid** with some pre-filled values.
2. The user can input a row, column, and number to fill the grid.
3. If the move is valid, the number is placed; otherwise, an error is shown.
4. The user can either solve it manually or use the **automated solver**.
5. Once complete, the solved Sudoku board is displayed.

## 📜 Methodology
- **Sudoku board** is represented as a **2D list** (9×9 grid).
- **Random puzzle generation** with at least 17 pre-filled numbers.
- **Move validation checks** (row, column, subgrid constraints).
- **Backtracking algorithm** for solving the puzzle recursively.
- **User interaction** via console-based inputs.

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sudoku-solver.git
   ```
2. Navigate to the project folder:
   ```bash
   cd sudoku-solver
   ```
3. Run the Python script:
   ```bash
   python sudoku_solver.py
   ```

## 🖼️ Output Example
```
Initial Board:
. 5 . | . . . | . . 1
. . . | 5 . . | . . .
. . . | . . . | . . .
---------------------
2 . . | . 5 4 | 7 . .
5 . . | . . . | . 8 .
. . . | . 6 . | . . .
---------------------
9 . . | 8 . . | . . .
8 . 2 | . . . | . . .
. . . | . . . | . 1 .
```
After solving:
```
8 5 3 | 7 2 9 | 6 4 1
7 2 9 | 5 1 6 | 8 3 4
1 4 6 | 3 8 4 | 2 9 5
---------------------
2 8 1 | 9 5 4 | 7 6 3
5 6 7 | 2 3 1 | 9 8 2
3 9 4 | 6 7 8 | 1 5 2
---------------------
9 7 5 | 8 4 2 | 3 1 6
8 3 2 | 1 9 5 | 4 7 8
4 1 8 | 6 7 3 | 5 2 9
```

## 🎯 Contributions
Feel free to contribute by submitting **pull requests** or reporting **issues**!

## 📜 License
This project is licensed under the **MIT License**.
