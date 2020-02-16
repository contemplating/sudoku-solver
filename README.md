# Sudoku Solver
basic interactive sudoku solver in Jupyter.

The first cell allows you to define the sudoku grid as an array. The last cell shows some examples of using the solver.

Currently there ar two solving mechanisms:

- solve() - solves the puzzle using backtracking
- solveSinglePossibilities() - puts in values into cells that only have once possibility. This fucntion can be repeated.

There is also a function *getPossibleValues()* that shows all possible values for a given cell.
