1. Steven Liao, 918615690
2. 
Q1. 
pacman's priority should be trying to survive means pacman should be running if ghost get too close
pacman's second priority is to eat all the food and higher game score means pacman is eating stuff
pacman's last priority is to travel to food and closer the food the higher better the position

Return negative infinity if a ghost is very close
Else return value which is the game score + reciprocal of distance to food

Q2.
Minimax function:

Base case:
If state is lose or win or if depth is 0
Pacman:
Run minimax on each successor and return max
Ghost:
    Last ghost:
	run minimax on next pacman successor and decrease depth by 1
    Other ghost:
	run minimax on next ghost successor and return minimum

Run minimax function on each state and record which action produced what score.

Return random action with highest score

Q4.
Same as Q2 but use average instead of minimum for ghost

Q5.
Return game score

3. 24 hrs