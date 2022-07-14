# SUDOKODE
#
* Trying to write an extremely basic and bruteforce style code to solve sudoku puzzles
* Sudoku puzzles contain a 9x9 grid of numbers such that no number is repeated in any of the row, column or the adjacent 2x3 blocks
* Objective is to create a code that can take in input through a gui grid that resembles a sudoku and give output in the same grid
#
#
## OUTLINE
#
1. Create gui grid array that can take input and also show the output.
2. Function to determine 'easiest' place to start adding number, i.e. the row, column or block with highest number of entries.
3. Function to check if there are any repeated numbers in row, column or block.
4. Function to add numbers to grid after confirming it is not repeated.
5. Backtrack any number of times in case a fit is not obtained
6. 