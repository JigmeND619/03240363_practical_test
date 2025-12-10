This repository contains solutions for the MLA202 practical test. The problems included in this practical test are on Q-Learning on GridWorld, Complete DQN for CartPole and Debugging Q-Learning.

Problem 1 was about implementing Q-learning to solve a 5×5 GridWorld with walls, problem 2 was about completing a partially implemented DQN agent for CartPole-v1 and, problem 3 was about identifying and fixing 4 bugs in FrozenLake Q-learning implementation.

Techniques Used for each Problem:

For Problem 1: Q-learning on the grid world.

Technique Used: Q-learning (tabular reinforcement learning strategy) Details: -- e-greedy action selection policy. --Q-table update rule: Q(s,a)←Q(s,a)+α[r+γa′max​Q(s′,a′)−Q(s,a)] --Parameters of learning: Learning rate, discount factor, exploration rate.

For Problem 2: CartPole Deep Q-Network (DQN).

Technique Used: Deep Q-Learning (neural network approximation of Q-values) Details: --Q-values are predicted by a neural network for every action. --Replay buffer experience for steady learning --ε-greedy exploration policy --Adam/Mean Squared Error loss optimizerTarget network on stability. --Target network for stability

For Problem 3: Comparison/ Debugging.

Technique Used: Q-learning performance analysis. Details: --Examine the differences between fixed and buggy Q-learning implementations. --Analyze the success rate and convergence --Plot-based visual comparison

Expected Outputs Are:

problem1_results.png - GridWorld training curves
problem2_results.png - CartPole DQN training
problem3_comparison.png - Buggy vs Fixed comparison
