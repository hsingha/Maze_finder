# Maze_finder

This project includes a maze consisting of a start point, end point, obstacles in the form of walls or pot holes etc. The bot will be placed at the starting point and will navigate itself to the finish point using the most optimal path. Incase of any detours, it does reroute itself.

Following were the technical tools used:
1) Python programming
2) Google Collab
3) Python libraries

Following are some topics (pre requisites) needed to be understood inorder to better grasp the concept:
1) Reinformcement Learning'
2) Dynamic Programming
3) Q Learning
4) SARSA
5) Policy Iteration
6) Value Iteration
7) Actor Critic

There were multiple iterations used in which the value of p, gamma and theta were changed to see if the bot takes different paths for each different combination, such as :
1) Gamma = 0.95, p = 0.02, theta = 0.01; Base Case Scenario
2) Gamma = 0.95, p = 0.5, theta = 0.01; Large Stochasticity Scenario
3) Gamma = 0.55, p = 0.02, theta = 0.01; Small Discount Factor
