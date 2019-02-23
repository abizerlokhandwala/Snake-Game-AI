# AI based Math Snake Game

A math based snake game, additional to the classical snake game, you have a question based on divisibility of a number, and the answer lies in one of the 3 apples on the map, which is to be consumed by the snake.  

This repo is a modification of the [math-snake-game](https://github.com/abizerlokhandwala/math-snake-game) repo, where I'm implementing an AI to play the game.

### Rules
1. If the snake consumes the right apple, it increments your score, while consuming the wrong one decrements it.
2. Everytime the snake consumes an apple, it's length increases by one and it's speed increases by a specified unit (No speed increment as of now).
3. Colliding with the rocky boundaries of the field or the obstruction (rock) in the field leads to an instant loss. 
4. 3 lives are given initially, consuming the wrong apple more than 3 times leads to a loss.

## Current AI implementation
1. Snake successfully finds the shortest path (Breadth First Search (BFS)) to the right apple, and maneuvers itself without colliding into its body or the boundary/rock obstruction.
2. Best human score uptil now was 31, BFS AI easily goes up to 100.
3. AI at times makes stupid decisions, traps itself in an attempt to eat an apple, which leads to it colliding with its body.
4. A* search algorithm is to be implemented, using a good heuristic to reduce the number of computations, and to make sure the AI does not trap itself.
5. Neural Network implementation is to be done too, using a genetic algorithm, spawning several generations of snakes and independently training/dumping them.
