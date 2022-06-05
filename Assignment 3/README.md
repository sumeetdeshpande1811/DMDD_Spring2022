Develop a Tic-tac-toe game using PL/SQL.

Tic-tac-toe is a game played between two players on a 3×3 grid. In a turn, a player chooses an empty cell and places their symbol on the cell. The players take alternating turns, where the player with the first turn uses the symbol X and the other player uses the symbol O. The game continues until there is a row, column, or diagonal containing three of the same symbol (X or O), and the player with that token is declared the winner. Otherwise, if every cell of the grid contains a symbol and nobody wins, then the game ends and it is considered a draw.

You are given a tic-tac-toe board AA after a certain number of moves, consisting of symbols O, X, and underscore(_). Underscore signifies an empty cell.

Print

 if the position is reachable, and the game has drawn or one of the players won.
 if the position is reachable, and the game will continue for at least one more move.
 if the position is not reachable.
Note:

Starting from an empty board, reachable position means that the grid is possible after a finite number of moves in the game where the players may or may not be playing optimally.
The answer for each test case should be with respect to the present position and independent of the results in the further successive moves

Also, do mention a few of the test cases in the submission file as well. 
Note: Treat the board as a table and using SQL Commands, PL/SQL to  perform operations respectively.