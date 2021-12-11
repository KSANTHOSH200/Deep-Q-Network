# Deep-Q-Network
Keras implementation of DQN (DQN.ipynb) for Breakout-v0 from OpenAI Gym.

Implements Deep Q-network (DQN) in Keras following the architecture proposed in the 2013 paper by V. Mnih et al., "Playing Atari with Deep Reinforcement Learning": arXiv:1312.5602. See:
http://www.davidqiu.com:8888/research/nature14236.pdf

The agent learns to play the Breakout-v0 Gym environment.

Hyperparameters were chosen according to the original paper. One key trick I found leads to better policies was introducing a fixed penalty of -1 at each action which did not naturally have a reward.
