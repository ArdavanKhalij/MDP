# MDP

## License
This project is licensed under the terms of the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Assignment 2: Tabular Reinforcement Learning in an MDP

This assignment provides an environment (ice.py, an MDP), and the skeleton of a Reinforcement Learning agent. The agent always performs action 0, in any state. It provides a Q-Table, but does not learn anything nor updates any Q-Value. The goal of this project is to complete this agent with:

- A Q-Learning rule that allows correct Q-Values to be learned. Beware that the environment is stochastic (need for a learning rate) and loopy (need for a discount factor if you don't want your agent to get stuck).
- An exploration strategy, for instance epsilon-greedy, that allows the agent to perform well in the environment and learn it fast.

It is possible to learn the task in one single (quite long) episode. You should therefore, at each time-step, print the current state, the action and the reward you obtain. This will allow us to measure the learning progress of your agent timestep per timestep.

The goal of this project is to learn the optimal policy as fast as possible. Bonus points are given for interesting exploration strategies, and for the project that achieves the fastest learning (ties both get the bonus).
