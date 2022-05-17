Steven Liao 
918615690

2. dfs
Create frontier with stack
Add start state to frontier
Create explored set to track visited nodes
Loop until frontier is empty
Get state from frontier
Return if state is goal
Else if state not in explored
Add state to explored
Then add successors to frontier

bfs
Same as dfs but use queue as frontier

ucs
Same as bfs but use priority queue as frontier
Use cost of actions function to find cost of moves to use as priority

astar
Same as ucs but add heuristic to priority for adding successors to frontier

corners problem
Use unvisited corners and position as state\

corners heuristic
Use manhattan distance to furthest corner as heuristic

food heuristic
Same as corners heuristic

suboptimal search
Use bfs to find closest food

3. 48 hrs

