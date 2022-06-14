# Lab 13

Check the file [`13_RL-PolicyBased.ipynb`](13_RL-PolicyBased.ipynb.ipynb)
which implements the cross-entropy method (CEM) on the [LunarLander](https://gym.openai.com/envs/LunarLander-v2/) environment.

This implementation is incomplete (and does not work). To fix it, implement the following:

1. Currently the state-action pairs of all episodes of one batch are used for training. To implement the Cross-Entropy-Method (CEM) correctly, use only the state-action pairs of the twenty best episodes in one batch in terms of highest reward.
2. Train the network with the correction from task 1.
3. After training, test the agent by running one episode using the trained network and record the episode
(see the notebooks from last week for code templates for recording.)