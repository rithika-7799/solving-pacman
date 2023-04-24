# solving-pacman

This modified version of Pacman features two agents, P and Q, instead of ghosts. Similar to the original game, there are fruits scattered throughout the maze that the agents can consume, with agent P able to eat fruits 1 and 2, and agent Q able to eat fruits 2 and 3. The objective of each agent is to eat all of its assigned fruits as quickly as possible. 

The agents achieve this goal using two algorithms: Iterative Deepening Search (IDS) and A*. The A* algorithm uses the Manhattan distance heuristic, which is both admissible and consistent. The algorithms are tested on boards of varying sizes to evaluate their performance.
