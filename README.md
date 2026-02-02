# Reinforcement Learning: Rookie to Rockstar

```
 ______  _                           _     _                                        _                          
(_____ \| |                         | |   (_)         _                            | |         _               
 _____) | |          ____ ___   ___ | |  _ _  ____   | |_  ___      ____ ___   ____| |  _  ___| |_  ____  ____ 
(_____ (| |         / ___/ _ \ / _ \| | / | |/ _  )  |  _)/ _ \    / ___/ _ \ / ___| | / )/___|  _)/ _  |/ ___)
      | | |_____   | |  | |_| | |_| | |< (| ( (/ /   | |_| |_| |  | |  | |_| ( (___| |< (|___ | |_( ( | | |    
      |_|_______)  |_|   \___/ \___/|_| \_|_|\____)   \___\___/   |_|   \___/ \____|_| \_(___/ \___\_||_|_|    
```

A course on Reinforcement Learning that starts from the ground up. The course is a series of (coming) YouTube videos where we build and train RL agents together. The Jupyter notebooks from the lectures are collected inside the `lectures` directory. Each lecture also has exercises listed in the video description. (This may grow into something more comprehensive over time.)

---

### Lecture 1: The spelled-out intro to reinforcement learning: building *Youbandit* 

We implement the simplest possible reinforcement learning agent: the YouTube Thumbnail Bandit. Each arm corresponds to a different thumbnail, and the reward is whether the user clicks. From scratch, we code up action selection, reward tracking, and incremental updates for estimating action values. This lecture focuses on (1) the idea of learning through interaction with an environment, (2) incremental gradient-like updates, (3) the core concepts of exploration vs. exploitation.  

---
### Lecture 2: The spelled-out intro to : building *Personalbandit*

We implement a one-step MDP, also known as a contextual bandit, applied to personalise a YouTube homepage. In follow-up videos, we will expand this into full reinforcement learning agents  operating in multi-step environments. In this lecture, the focus is on (1) introducing states in the RL loop of state → action → reward, (2) build a 2D belief table which opens up having a personalised strategy, (3) introducing and showing how subtle bugs can be hard to spot in RL research, (4) hinting about the need for agents that can generalise.
