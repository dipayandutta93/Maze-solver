# Maze-solver

We implemented DFS, BFS and A-star algorithm to find the shortest path from start to the end within the maze.

![image](https://user-images.githubusercontent.com/32987993/40892371-34d86f0a-6764-11e8-9eae-29774c736fb0.png)

![image](https://user-images.githubusercontent.com/32987993/40892372-3a67dbf4-6764-11e8-9d0b-167e7a2d433f.png)

![image](https://user-images.githubusercontent.com/32987993/40892373-3ec68916-6764-11e8-879d-e6c7c16d2e76.png)

Then we try to generate harder mazes using Genetic algorithm and simulated Annealing.

Genetic Algorithm uses the following criteria when trying to generate better solutions:
1. Crossover
2. Mutation

Simulated Annealing uses Mutation as the sole criteria for generating better solutions. However, Simulated Annealing with slow cooling and significant number of iterations we can reach to global maxima. So, to compare these algorithms theoretically is inconclusive. Furthermore, Genetic Algorithms are better suited when operated upon a large population. Here our population is a set of mazes from which we generate tough mazes. By tough we mean the mazes which are hard to solve by our search algorithms. We define hardness by the number of nodes expanded by our search algorithm. Genetic algorithm provided us with a larger diversity which increases the chances of getting harder mazes. Finally, we run both algorithms and select the one that generates tougher maze.
