# Sudoku Solver
RESTful API that solves Sudoku puzzles.

The API can be accessed by sending a POST request to the following URL, with the Sudoku puzzle in the body of the request:
https://sudoku-solver.freecodecamp.rocks/api/solve

The request body should be a string containing the Sudoku puzzle in the following format:
.9..5.1.85.4....2432......1...69.83.9.....6.62.71...9......1945....4.37.4.3..6..

The periods (.) represent empty spaces.

The response will be a JSON object with the following properties:
{
  "solution": ".9..5.1.85.4....2432......1...69.83.9.....6.62.71...9......1945....4.37.4.3..6.."
}
The solution property contains the solved Sudoku puzzle.

The API is implemented using the Express framework and Node.js. The Sudoku solving algorithm is based on the backtracking algorithm.

You can see the live version of the code and running app in my Repl: https://replit.com/@polpages1999/sudoku-solver?v=1
