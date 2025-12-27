# SHORTEST_PATH_IN_GRID_WITH_OBSTACLES_ELIMINATION_REINFORCEMENT_LEARNING
Solving Shortest Path in Grid with Obstacles Elimination using Reinforcement Learning
- Build a learnable agent who with trial and error learns about the environment to solve the problem.
1. Agent: An agent is a hypothetical entity that controls the course of action. Agent has two possible options : position (0, 0) that goes right or to position (0, 1) that goes down, and both these positions have different rewards.
2. Environment: The environment is the context in which our agent operates which is a two dimensional—a grid in this case.
3. 4. State: State represents current situation of the player. In our case, it gives current position of the player and the number of remaining violations.
5. Reward System: reward is the score we get as a result of taking a certain action. In this case : -1 points for an empty cell, +20 points for reaching the destination and -10 points if we run out of the number of violations, k.
   
Q Function

- Q^{\pi }(s,a) represents the expected cumulative reward an agent can achieve by taking action a in state s, while following policy π.
  
Where:

π : the policy adopted by the agent.
s : the current state.
a : the action taken by the agent in state s.
