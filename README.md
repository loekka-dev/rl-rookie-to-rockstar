# Reinforcement Learning: Rookie to Rockstar

A course on Reinforcement Learning that starts from the ground up. The course is a series of YouTube videos where we build and train RL agents together. The Jupyter notebooks from the lectures are collected inside the `lectures` directory. Each lecture also has exercises listed in the video description. (This may grow into something more comprehensive over time.)

---
### Lecture 1: The spelled-out intro to reinforcement learning: building *banditgrad* 
We implement the simplest possible reinforcement learning agent: a k-armed bandit. From scratch, we code up action selection, reward tracking, and incremental updates for estimating action values. This lecture focuses on (1) the idea of learning through interaction with an environment, (2) incremental gradient-like updates without backpropagation, and (3) the core concepts of exploration vs. exploitation.  
---
### Lecture 2: The spelled-out intro to : building *clickmore*
We implement a one-step MDP, also known as a contextual bandit, applied to banner ad placement. In follow-up videos, we will expand this into full reinforcement learning agents operating in multi-step environments. In this lecture, the focus is on (1) introducing the RL loop of context → action → reward, (2) implementing policy evaluation and simple policy updates, and (3) establishing the overall framework of reinforcement learning that includes exploration, exploitation, and the evaluation of cumulative reward.
