# cpp-project
# N-Queens

o Domain: DSA | Programming Language: C++

The N-Queens project is a C++ implementation of a backtracking algorithm to solve the classic N-Queens problem on a chessboard. The goal is to arrange N queens on an NxN chessboard in such a way that no two queens can attack each other. In chess, queens can move vertically, horizontally, and diagonally, so the challenge is to place the queens in non-attacking positions.
    
The program utilizes object-oriented programming (OOP) concepts and creates an efficient data structure using a 2D array (grid) to represent the chessboard and store the queen positions. The backtracking algorithm systematically explores possible configurations and checks for a valid solution while avoiding conflicts between queens.


**Input 1:**
```input
Enter the number of Queen: 4
```
**Output 1:**
```output
0 | 1 | 0 | 0 | 
0 | 0 | 0 | 1 | 
1 | 0 | 0 | 0 | 
0 | 0 | 1 | 0 | 


0 | 0 | 1 | 0 | 
1 | 0 | 0 | 0 | 
0 | 0 | 0 | 1 | 
0 | 1 | 0 | 0 | 
```
**Input 2:**
```input
Enter the number of Queen: 3
```
**Output 2:**
```output
-1
```

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Sudoku

o Domain: DSA | Programming Language: C++

The Sudoku Solver project is a C++ implementation of a backtracking algorithm to solve a 9x9 Sudoku puzzle. Sudoku is a number puzzle where the goal is to fill a 9x9 grid with digits from 1 to 9, following specific rules:

- Each row must contain all digits from 1 to 9 without repetition.
- Each column must contain all digits from 1 to 9 without repetition.
- Each of the nine 3x3 subgrids (also known as boxes) must contain all digits from 1 to 9 without repetition.

The program uses a backtracking approach to efficiently explore possible solutions for the Sudoku puzzle. It starts by finding an empty cell (marked with 0) in the grid and tries different numbers (from 1 to 9) for that cell, ensuring that the number does not violate the Sudoku rules. If the number is valid, the program recursively moves to the next empty cell and repeats the process. If the program reaches a point where it cannot find a valid number for the current cell, it backtracks to the previous cell and tries a different number, eventually exploring all possible combinations until a valid solution is found.

**Input 1:**
```input
3 0 6  | 5 0 8  | 4 0 0 
5 2 0  | 0 0 0  | 0 0 0 
0 8 7  | 0 0 0  | 0 3 1 
---------------------------
0 0 3  | 0 1 0  | 0 8 0 
9 0 0  | 8 6 3  | 0 0 5 
0 5 0  | 0 9 0  | 6 0 0 
---------------------------
1 3 0  | 0 0 0  | 2 5 0 
0 0 0  | 0 0 0  | 0 7 4 
0 0 5  | 2 0 6  | 3 0 0 
```
**Output 1:**
```output
3 1 6  | 5 7 8  | 4 9 2 
5 2 9  | 1 3 4  | 7 6 8 
4 8 7  | 6 2 9  | 5 3 1 
---------------------------
2 6 3  | 4 1 5  | 9 8 7 
9 7 4  | 8 6 3  | 1 2 5 
8 5 1  | 7 9 2  | 6 4 3 
---------------------------
1 3 8  | 9 4 7  | 2 5 6 
6 9 2  | 3 5 1  | 8 7 4 
7 4 5  | 2 8 6  | 3 1 9  
```
**Input 2:**
```input
3 0 6  | 5 0 2  | 4 0 0 
5 2 0  | 0 0 0  | 0 0 0 
0 8 7  | 0 0 0  | 0 3 1 
---------------------------
2 0 3  | 0 1 0  | 0 8 0 
9 0 0  | 8 6 3  | 0 0 5 
0 5 0  | 0 9 0  | 6 0 0 
---------------------------
1 3 0  | 0 0 0  | 2 5 0 
0 0 0  | 0 0 0  | 8 7 4 
0 0 5  | 2 0 6  | 3 0 0 
```
**Output 2:**
```output
No solution exists
```




