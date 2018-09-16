# tetris

REPORT for part 2:
Initial State: Empty board with 20 rows and 10 columns
Valid states: A set of successors where new piece of size 4 is placed 
Successor function: Set in which all possible rotations of the piece placed on each column after checking collision .
Goal State: Player looses when no piece can be placed on the board(i.e. the top row of board has a (part of ) piece
1) Algorithm: Generates successors for the piece and finds the best possible place using heuristic
2) heuristic: Following things are considered in the heuristic:
  a) increase in height
  b) change in number of holes
  c) no of blockings added
  d) award for no of clears
3)Problems faced:
  a) Designing the heuristic
  b) assigning weights to each parameters in the heuristic
  
Author: Sucessor, heuristic, getmoves, and all functions related to heuristic by Sairam Rakshith bhyravabhotla
Others: David Crandall. 
functions from TetrisGame() object used from TetrisGame.py written by David Crandall.
