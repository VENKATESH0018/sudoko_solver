# Sudoku Solver
A Java-based Sudoku Solver that uses backtracking to solve 9x9 Sudoku puzzles efficiently. This project showcases problem-solving techniques like recursion and constraint satisfaction.

Features
Solves standard 9x9 Sudoku puzzles.
Validates numbers to follow Sudoku rules (rows, columns, and 3x3 sub-grids).
Displays all possible solutions for the given puzzle.
Implements a clean and modular code structure for easy understanding.
Input and Output
Input Example
The program takes a Sudoku puzzle as a 9x9 grid where:

0 represents empty cells.
Numbers 1-9 are pre-filled values.
Example:

3 0 6 5 0 8 4 0 0  
5 2 0 0 0 0 0 0 0  
0 8 7 0 0 0 0 3 1  
0 0 3 0 1 0 0 8 0  
9 0 0 8 6 3 0 0 5  
0 5 0 0 9 0 6 0 0  
1 3 0 0 0 0 2 5 0  
0 0 0 0 0 0 0 7 4  
0 0 5 2 0 6 3 0 0  
Output Example
The program outputs the solved puzzle:

3 1 6 5 7 8 4 9 2  
5 2 9 1 3 4 7 6 8  
4 8 7 6 2 9 5 3 1  
2 6 3 4 1 5 9 8 7  
9 7 4 8 6 3 1 2 5  
8 5 1 7 9 2 6 4 3  
1 3 8 9 4 7 2 5 6  
6 9 2 3 5 1 8 7 4  
7 4 5 2 8 6 3 1 9  
How to Run
Clone this repository:
git clone https://github.com/your-username/sudoku-solver.git
Navigate to the project folder.
Compile the program:
javac sudoko.java
Run the program:
java sudoko
Tech Stack
Language: Java
Algorithm: Backtracking
Use Cases
Solve Sudoku puzzles programmatically.
Learn and understand backtracking algorithms.
Explore practical applications of recursion and modular coding.
