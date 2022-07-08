# LoShuMagicSquare
A simple resolution to the Lo Shu Magic Square common algorithm excercise.  This is commonly known as "SUDOKU".

## The problem
Print to the console one matrix of 3x3 that holds numbers from 1 to 9, and the sum of each line, column or diagonal are equal to 15.

_Example:_   
           8  1  6   
           3  5  7  
           4  9  2  

_Rows sum:_ 
8 + 1 + 6 = 15
3 + 5 + 7 = 15
4 + 9 + 2 = 15

_Columns sum:_
8 + 3 + 4 = 15
1 + 5 + 9 = 15
6 + 7 + 2 = 15

_Diagonals sum:_
8 + 5 + 2 = 15
6 + 5 + 4 = 15

## The solution
Make a 3x3 matrix and changes the values of each index based on the sum of index, columns as diagonals.
