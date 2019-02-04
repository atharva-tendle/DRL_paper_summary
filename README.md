# Summary of key papers in Deep Reinforcement Learning

This repository contains the summary of key papers in deep reinforcement learning listed in OpenAI [Spinning Up](https://spinningup.openai.com/en/latest/index.html). The summaries aim to provide a high-level overview of each paper, listing out the key problems the authors tried to solve and the main contributions / algorithms proposed. While technical details are omitted in these summaries, it doesn't mean they are overlooked, and readers are encouraged to read the original papers should they have any interests in digging more into this field.

### 1. Model-Free Reinforcement Learning

#### a. Deep-Q-Learning

[1] Playing Atari with Deep Reinforcement Learning, Mnih et al, 2013. **Algorithm: DQN.** [[paper](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)] [[summary](https://github.com/RPC2/DRL_paper_summary/blob/master/001%20Playing%20Atari%20with%20Deep%20Reinforcement%20Learning.md)]

[2]Deep Recurrent Q-Learning for Partially Observable MDPs, Hausknecht and Stone, 2015. **Algorithm: Deep Recurrent Q-Learning.** [[paper](https://arxiv.org/abs/1507.06527)] [[summary](https://github.com/RPC2/DRL_paper_summary/blob/master/01%20Model-Free%20RL/002%20Deep%20Recurrent%20Q-Learning%20for%20Partially%20Observable%20MDPs.md)]

[3] Dueling Network Architectures for Deep Reinforcement Learning, Wang et al, 2015. **Algorithm: Dueling DQN.** [[paper](https://arxiv.org/abs/1511.06581)]

[4] Deep Reinforcement Learning with Double Q-learning, Hasselt et al 2015. **Algorithm: Double DQN.** [[paper](https://arxiv.org/abs/1509.06461)] 

[5] Prioritized Experience Replay, Schaul et al, 2015. **Algorithm: Prioritized Experience Replay (PER).** [[paper](https://arxiv.org/abs/1511.05952)] [[summary](https://github.com/RPC2/DRL_paper_summary/blob/master/01%20Model-Free%20RL/005%20Prioritized%20Experience%20Replay.md)]

[6] Rainbow: Combining Improvements in Deep Reinforcement Learning, Hessel et al, 2017. **Algorithm: Rainbow DQN.** [[paper](https://arxiv.org/abs/1710.02298)] 

#### b. Policy Gradients

[7] Asynchronous Methods for Deep Reinforcement Learning, Mnih et al, 2016. **Algorithm: A3C.** [[paper](https://arxiv.org/abs/1602.01783)] [[summary](https://github.com/RPC2/DRL_paper_summary/blob/master/01%20Model-Free%20RL/007%20Asynchronous%20Methods%20for%20Deep%20Reinforcement%20Learning.md)]

[8] Trust Region Policy Optimization, Schulman et al, 2015. **Algorithm: TRPO.** [[paper](https://arxiv.org/abs/1502.05477)]

[9] High-Dimensional Continuous Control Using Generalized Advantage Estimation, Schulman et al, 2015. **Algorithm: GAE.** [[paper](https://arxiv.org/abs/1506.02438)]

[10] Proximal Policy Optimization Algorithms, Schulman et al, 2017. **Algorithm: PPO-Clip, PPO-Penalty.** [[paper](https://arxiv.org/abs/1707.06347)]

[11] Emergence of Locomotion Behaviours in Rich Environments, Heess et al, 2017. **Algorithm: PPO-Penalty.** [[paper](https://arxiv.org/abs/1707.02286)]

[12] Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation, Wu et al, 2017. **Algorithm: ACKTR.** [[paper](https://arxiv.org/abs/1708.05144)] [[summary](https://github.com/RPC2/DRL_paper_summary/blob/master/01%20Model-Free%20RL/012%20Scalable%20trust-region%20method%20for%20deep%20reinforcement%20learning%20using%20Kronecker-factored%20approximation.md)]

[13] Sample Efficient Actor-Critic with Experience Replay, Wang et al, 2016. **Algorithm: ACER.** [[paper](https://arxiv.org/abs/1611.01224)]

[14] Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor, Haarnoja et al, 2018. **Algorithm: SAC.** [[paper](https://arxiv.org/abs/1801.01290)]