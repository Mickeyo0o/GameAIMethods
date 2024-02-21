# Game AI Methods

This project showcases various artificial intelligence methods applied to popular games, including Sudoku, Tic-Tac-Toe, and Migration.

## Games Included

* Sudoku: The Sudoku problem is treated as a Constraint Satisfaction Problem (CSP). The following methods are implemented:
   * Recursive Backtracking with Minimum Remaining Value (MRV) and Degree Heuristics.
  * Recursive Backtracking with the above heuristics and Arc Consistency 377 Algorithm.

* Tic-Tac-Toe: Implemented using Minimax and Alpha-Beta Pruning algorithms. A heuristic is applied to improve performance, especially for the more complex Migration game.

* Migration: Similar to Tic-Tac-Toe but with a larger board and additional rules. It's solved using the same algorithms as Tic-Tac-Toe, but with optimizations to handle the increased complexity.

## Methods Implemented

* Recursive Backtracking: A common method for solving CSPs like Sudoku.
* Minimum Remaining Value (MRV): Heuristic to choose the variable that is most constrained.
* Degree Heuristic: Heuristic to choose the variable that is involved in the largest number of constraints.
* Arc Consistency 3 Algorithm: A constraint propagation technique to reduce the search space further.
* Minimax Algorithm: Used for adversarial search in games like Tic-Tac-Toe and Migration.
* Alpha-Beta Pruning: An optimization technique to reduce the number of nodes evaluated in the minimax algorithm.
* Maximal Remaining Moves and Maximal Blocked Oponnents Heuristic
* Alpha-Beta Pruning with limited depth and heuristics.

## Performance Considerations

*  The choice of algorithm and heuristic significantly impacts the performance of solving the games.
*  Heuristics like MRV and Degree help in choosing the most promising variables, reducing the search space.
*  Arc Consistency 3 Algorithm further prunes the search space by enforcing constraints.
*  In games like Tic-Tac-Toe and Migration, alpha-beta pruning with heuristics improves performance by reducing the number of evaluated nodes, but additionally lowers the algorithm complexity, resulting in worse performance against other player.
 
## Creator

This project was created by  Mikołaj Marmurowicz (Mickeyo0o).