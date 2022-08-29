# Example Categorical DQN implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_categorical_dqn_example/blob/master/categorical_dqn_tutorial.ipynb) of categorical deep q-network (Categotical DQN) with ReLAx.

Categotical DQN actor was trained on Breakout-v0 Atari Gym environment for 3m env-steps. 

__!Note:__ For demonstration purposes training was run only for 3m steps. In papers, DQN and its augmentations are trained for 200m steps, which may require several days of learning. That is why performance is lower than reported in papers.

The graph of average return vs environment step is shown below (logs done every 50k steps):

![categorical_dqn_training](https://github.com/nslyubaykin/relax_categorical_dqn_example/blob/master/categorical_dqn_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![categorical_dqn_q_func](https://github.com/nslyubaykin/relax_categorical_dqn_example/blob/master/categorical_dqn_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187174060-a46bd1c6-50a2-4ed7-9741-41bfb7ab313a.mp4
