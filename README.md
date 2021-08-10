# REINFORCEMENT LEARNING AGENT

This project was a part of the Reinforcement learning course (CS6700) Jan-May 2021 at IIT Madras. The project involved deploying a reinforcement learning agent in order to be able to solve discrete environments. In the test set, 3 environments were tested in particular. This repository consists of the reinforcement learning agent based on Q-learning algorithm. For exploration, we employed stragies such as epsilon constant, epsilon greedy and boltzmann exploration.

We observed that boltzmann exploration converges faster for complex environments. However, for simple enough environments, epsilon greedy generally plays a better role.

Also, we noticed that the function we employed when using epsilon greedy as well plays a very improtant role for convergence. It was of improtance for one to ensure that initially that the agent can explore a lot. However, after an optimal number of exploration steps, we could rapidly reduce the epsilon value at an exponential rate to obtain convergence.

boltzmann_exploration.ipynb - Comprises code for boltzmann exploration
epsilon_greedy_exploration.ipynb - Comprises code for epsilon greedy approach

Link to the competition page : https://www.aicrowd.com/challenges/iitm-rl-final-project

We were placed 9th in the leaderboard.




