# SnakeGame-AI

This repo is a modification of the SnakeGame(https://github.com/ankita0018/SnakeGame) repo, where I'm implementing an AI to play the game.

Game can be played here: https://ankita0018.github.io/SnakeGame-AI/

A math based snake game, additional to the classical snake game. 

You have a question based on divisibility of a number, and the answer lies in one of the 3 apples on the map, which is to be consumed by the snake.

Rules:

1. If the snake consumes the right apple, it increments your score, while consuming the wrong one          decrements it.
2. Everytime the snake consumes an apple, it's length increases by one and it's speed increases.
3. Colliding with the rocky boundaries of the field or the obstruction (rock) in the field leads to an      instant loss.
4. 3 lives are given initially, consuming the wrong apple more than 3 times leads to a loss.

AI Implementation

1. The snake successfully finds the shortest path, using the Breadth First Search(BFS), to the right        apple, and operates without colliding into its body or the boundary/rock barrier.
2. AI at times makes stupid decisions, traps itself in an attempt to eat an apple, which leads to it        colliding with its body.
3. AI search algorithm is to be implemented, using a good hands-on approach to reduce the number of        computations, and to make sure the AI does not trap itself.
4. Neural Network implementation is to be done too, using a genetic algorithm, spawning several            generations of snakes and independently training/dumping them.
5. BFS AI easily goes upto 100.
