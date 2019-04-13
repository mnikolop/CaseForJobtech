# CaseForJobtech
This code is a solution for the case possed in the Jobtech interview process.

It is the Daily Coding Problem: Problem #23 (This problem was asked by Google).

You are given an M by N matrix consisting of booleans that represents a board. Each True boolean represents a wall. Each False boolean represents a tile you can walk on.

Given this matrix, a start coordinate, and an end coordinate, return the minimum number of steps required to reach the end coordinate from the start. If there is no possible path, then return null. You can move up, left, down, and right. You cannot move through walls. You cannot wrap around the edges of the board.

The solution was made in Python and coded in a Jupyter notebook.
pThe solution takes input from the user for the matrix size as well as the position of the starting and exit point. Witht hat information it generates a dataframe witht eh given size and marks the positions of the given points, the "walls" are generated randomly.

Next the solution checks for lines or rows that are completely covered in "walls", as well as if the start and exit points are serounded by "walls" *bug1: these checks are not working properly*

Next the space between the start and exit points is covered in numbers representing the steps from the starting point to the end *bug2: it does not cover the whole grid and it ends if it has to go backward.
bug3: it counts an extra step when it reaches the end of a row.*
