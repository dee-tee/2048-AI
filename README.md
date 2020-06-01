# 2048-AI
This project uses the Monte-Carlo Algorithm to create an AI for the 2014 game 2048.
This project is written in Python and I have used the numpy and tkinter libraries.
# About 2048
2048 is played on a 4×4 grid, with numbered tiles that slide smoothly when a player moves them using the four arrow keys. Every turn, a new tile will randomly appear in an empty spot on the board with a value of either 2 or 4. (Probability of 90%: 2, 10%: 4) Tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid. If two tiles of the same number collide while moving, they will merge into a tile with the total value of the two tiles that collided. (https://en.wikipedia.org/wiki/2048_(video_game))
# About the Monte Carlo Approach
The underlying concept of the Monte Carlo method is to use randomness to solve problems that might be deterministic in principle.An attempt is made so as to determine what is a good move by playing multiple random games upto the point where no further moves are possible and backtracking the first move of the game. The scores of each random game are recorded and the first move of the game which results in the maximum score is selected as the next move and the process is repeated at each stage until the game is over.
An increase in the random number of games played per move, results in a better endscore.
# Improvements
We can also add a counter which calculates the number of moves a random game is able to play before termination of the game and use it as a score to optimise the algorithm.
# Credit and Sources
https://github.com/silverstar194/2048-ai-monte-carlo
https://en.wikipedia.org/wiki/Monte_Carlo_method
https://www.youtube.com/watch?v=OgO1gpXSUzU
