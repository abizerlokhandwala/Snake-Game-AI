# AI based Math Snake Game

A math based snake game, additional to the classical snake game, you have a question based on divisibility of a number, and the answer lies in one of the 3 apples on the map, which is to be consumed by the snake.  

This repo is a modification of the [math-snake-game](https://github.com/abizerlokhandwala/math-snake-game) repo, where I'm planning to add an AI to play the game.

### Rules
1. If the snake consumes the right apple, it increments your score, while consuming the wrong one decrements it.
2. Everytime the snake consumes an apple, it's length increases by one and it's speed increases by a specified unit (No speed increment as of now *testing*).
3. Colliding with the rocky boundaries of the field or the obstruction (rock) in the field leads to an instant loss. 
4. 3 lives are given initially, consuming the wrong apple more than 3 times leads to a loss.
