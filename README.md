# tic-tac-toe-with-ai

To start the game enter: 
Input command: > start {level} user
{level} - player X
user - player O

The order is matter:
Input command: > start user {level}
user - player X
{level} - player O

There are three level: "easy", "medium", "hard"

Write the coordinates of your move in the way: x y, where x the column and y - the row:
Enter the coordinates: > 2 2
---------
|       |
|   O   |
|       |
---------

To exit write:
Input command: > exit

Example:
Input command: > start hard user
Making move level "hard"
---------
|       |
| X     |
|       |
---------
Enter the coordinates: > 2 2
---------
|       |
| X O   |
|       |
---------
Making move level "hard"
---------
|   X   |
| X O   |
|       |
---------
Enter the coordinates: > 3 2
---------
|   X   |
| X O   |
|   O   |
---------
Making move level "hard"
---------
| X X   |
| X O   |
|   O   |
---------
Enter the coordinates: > 3 1
---------
| X X   |
| X O   |
| O O   |
---------
Making move level "hard"
---------
| X X X |
| X O   |
| O O   |
---------
X wins

Input command: > exit
