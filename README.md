# CodeAlpha_-SudokuSolver-

A simple C++ Sudoku solver using backtracking.

## Features

- Solves standard 9x9 Sudoku puzzles.
- Prints the puzzle and its solution in a readable format.

## Usage

1. **Build the program**  
   Compile the source file using a C++ compiler, for example:


   
3. **Modify the puzzle**  
Edit the initial board in [`Task3.cpp`](Task3.cpp) to solve a different puzzle.

## File Structure

- [`Task3.cpp`](Task3.cpp): Main source code for the Sudoku solver.
- [`README.md`](README.md): Project documentation.
- [`.gitignore`](.gitignore): Git ignore rules.

## Example Output
Sudoku Puzzle: 5 3 0 | 0 7 0 | 0 0 0 6 0 0 | 1 9 5 | 0 0 0 0 9 8 | 0 0 0 | 0 6 0
8 0 0 | 0 6 0 | 0 0 3 4 0 0 | 8 0 3 | 0 0 1 7 0 0 | 0 2 0 | 0 0 6
0 6 0 | 0 0 0 | 2 8 0 0 0 0 | 4 1 9 | 0 0 5 0 0 0 | 0 8 0 | 0 7 9

Solution: 5 3 4 | 6 7 8 | 9 1 2 6 7 2 | 1 9 5 | 3 4 8 1 9 8 | 3 4 2 | 5 6 7
8 5 9 | 7 6 1 | 4 2 3 4 2 6 | 8 5 3 | 7 9 1 7 1 3 | 9 2 4 | 8 5 6
9 6 1 | 5 3 7 | 2 8 4 2 8 7 | 4 1 9 | 6 3 5 3 4 5 | 2 8 6 | 1 7 9
