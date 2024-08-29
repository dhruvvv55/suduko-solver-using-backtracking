# suduko-solver-using-backtracking
This repository includes a Python-based Sudoku solver that solves a given Sudoku puzzle by applying the backtracking algorithm. When a valid solution is found, the solver verifies that it adheres to the conventional Sudoku rules.

<h2>Features</h2>

1. Solves any 9x9 Sudoku puzzle that is valid.

2. Uses the backtracking technique to solve problems quickly and effectively.

3. Produces a solution output that is readable and clear.

<h2>How It Works</h2>

1. Input: Zeros are used to indicate empty cells in the 9x9 grid used to input the Sudoku problem.

2. Backtracking Algorithm: Assuring that every digit complies with Sudoku rules, the solver attempts digits 1 through 9 to fill in vacant cells. When a contradiction is discovered, the solver goes back to earlier cells and attempts with alternative digits.

3. Output: The finished Sudoku grid is produced by the solver.
