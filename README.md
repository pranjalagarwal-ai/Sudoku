# Sudoku
Sudoku Solver

Sudoku Solver using C++

In this project we will solve Sudoku problem using C++. 
Assumption:
•	Here we use 9*9 matrix to input values between 0-9 in our Sudoku where 0 represents empty space and rest are valid inputs.

Function Used:
•	canPlace9x9(): This function will check the condition whether our cell is empty or not. The function takes four parameters array, size of row, size of column and number we want to input and will return TRUE if the cell is empty else will return FALSE.
•	solveSudoku9x9(): This function will return TRUE if Sudoku is solvable else will return FALSE. It takes three parameters array, size of row and column.
•	findPlaceables(): This function returns set of numbers that can be placed at the cell.
•	copyArray(): This function will copy the value placed into another array.
•	nextEmpty(): This function will find next empty row and column indexes for the value to be palced.
•	printSudoku9x9(): This function will print the Sudoku.

