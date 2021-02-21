# 8-Puzzle-game-using-dfs
 ​ First initiating the root node and then call the dfs function, it prints out the entire solution path from root node to the solution node.
 Having a lot of attributes that define each node which are :state , parent, action, depth ,cost and the children node.
Then having 4 possible moves thus having 4 functions for moving (up, down, right, left), 
those functions return the new state and tile value that has been moved and if moving is not possible, it returns false. 
There is a print path function for printing the solution. 
Then There is a dfs function, in this function first start calculating time, declaring some variables and  start looping until the stack is empty.
while looping: pop the first element in the stack, the depth and the cost 
then adding them to an empty set called visited and comparing this node with the goal node if yes, then print it.
Else I try possible moves. 
The loop keep repeating till the goal state is reached. 
