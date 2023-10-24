# Lab-4
Lab 04 Exercise 3 of ProgrammingTechniques Politecnico Di Torino
Iterations on matrixes
A text file contains an array of integers with the following format:
• the first line of the file specifies the dimensions of the matrix (number of rows nr and number of columns nc)nc), separated by spaces Assume that both values are <= 20.
• each of the subsequent lines contains the NC values corresponding to a row of the matrix, with one or more spaces as separators.
Write a C program that:
• reads this matrix from the input file (the name of the file, maximum 20 characters, is read from the keyboard)
• repeatedly asks the user for a dim value between 1 and the minimum between nr and nc and prints all the square sub-matrixes of size dim that are contained in the input matrix
• prints the square sub-matrix, among those previously identified, that has the maximum sum of elements
• terminates the iterations if the user enters a value that is inconsistent with the size of the matrix
Example
If the content of the input file is the following: of the input file is the following:
3 4
1 2 3 4
5 6 7 8
9 0 1 1
and dim=2dim=2, the program should print on the screen the program should print on the screen::
The square sub--matrixes of dimension 2 are matrixes of dimension 2 are:
1 2
5 6

2 3
6 7

3 4
7 8

5 6
9 0

6 7
0 1

7 8
1 1
The submatrix with the maximum sum of elements (22) is: elements (22) is:
3 4
7 8
