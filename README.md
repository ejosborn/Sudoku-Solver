# Sudoku-Solver
This Sudoku solver solves a partially complete sudoku board using a backtracking algorithm.
There are 3 files: SudokuSolve.py, solveForGUI.py, and GUI.py.
# SudokuSolve.py:
This python file solves a partially complete sudoky board in the IDE terminal or python terminal.
# solveForGUI.py
This python file is used by GUI.py to see if an user inputted answer in the GUI is valid from the validate method, and depending on the returned boolean, the solveSudoku method will add the answer to the board or reject it if it does not see a possible solution.
# GUI.py
This python file creates a GUI for the Sudoku Solver using pygame. The coded GUI creates a grid for the paritally comnplete sudoku board, cells for the numbers, number of strikes or wrong inputted answers, and tracks the time. The user is then prompted to try and solve the sudoku puzzle. If the user inputs an incorrect answer, a strike is given at the bottom left of the GUI
