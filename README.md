# CaseForJobtech
This code is a solution for the case possed in the Jobtech interview process.

It is the Daily Coding Problem: Problem #23 (This problem was asked by Google).

The solution was made in Python and coded in a Jupyter notebook.
pThe solution takes input from the user for the matrix size as well as the position of the starting and exit point. Witht hat information it generates a dataframe witht eh given size and marks the positions of the given points, the "walls" are generated randomly.

Next the solution checks for lines or rows that are completely covered in "walls", as well as if the start and exit points are serounded by "walls" *bug1: these checks are not working properly*

Next the space between the start and exit points is covered in numbers representing the steps from the starting point to the end *bug2: it does not cover the whole grid and it ends if it has to go backward.*
