# PRODIGY_SD_04

Sudoku Solver--->> Create a program that solves Sudoku puzzles automatically. The program should take an input grid representing an unsolved Sudoku puzzle and use an algorithm to fill in the missing numbers. It should use backtracking or other suitable techniques to explore possible solutions and find the correct arrangement of numbers for the puzzle. Once solved, the program should display the completed Sudoku grid.

Explanation:---->>> isSafe(): Checks if it's safe to place a number num in the specified row and column of the Sudoku board.

findEmptyLocation(): Finds an empty location in the Sudoku board.

solveSudoku(): Uses backtracking to solve the Sudoku puzzle. It tries each number from 1 to 9 in an empty cell and recursively checks if the puzzle can be solved with that number.

printBoard(): Prints the solved Sudoku board.

main(): Initializes a Sudoku puzzle and attempts to solve it using the solveSudoku() function.
