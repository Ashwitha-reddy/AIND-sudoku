#Artificial Intelligence Nanodegree
#Introductory Project: Diagonal Sudoku Solver

Q: How do we use constraint propagation to solve the naked twins problem?  
A:Constraint Propagation is all about using local constraints in a space 
 to dramatically reduce the search space. As we enforce each constraint, 
 we see how it introduces new constraints for other parts of the board that
 can help us further reduce the number of possibilities.
 Naked twin is a constraint to reduce the number of possibilities in which 
 repeatedly the constraint is applied to solve the problem until it reaches the 
 goal state.
 
 

Q: How do we use constraint propagation to solve the diagonal sudoku problem?  
A: A diagonal sudoku is like a regular sudoku, except that among the two main 
  diagonals, the numbers 1 to 9 should all appear exactly once. 
  we use constraint propagation to solve the diagonal problem by taking a
  diagonal unit and considering the peers being only diagonal boxes and applying 
  the reduction methods until  diagonal units are filled and solved.
  

