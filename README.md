                                                                                                                                                                                                                        
88888888ba   88                                                     88         88                                                                                88                                                     
88      "8b  88                                                     88         ""                    ,d                                                          88                      ,d                             
88      ,8P  88                                                     88                               88                                                          88                      88                             
88aaaaaa8P'  88               8b,dPPYba,   ,adPPYba,    ,adPPYba,   88   ,d8   88   ,adPPYba,      MM88MMM  ,adPPYba,       8b,dPPYba,   ,adPPYba,    ,adPPYba,  88   ,d8   ,adPPYba,  MM88MMM  ,adPPYYba,  8b,dPPYba,  
88""""88'    88               88P'   "Y8  a8"     "8a  a8"     "8a  88 ,a8"    88  a8P_____88        88    a8"     "8a      88P'   "Y8  a8"     "8a  a8"     ""  88 ,a8"    I8[    ""    88     ""     `Y8  88P'   "Y8  
88    `8b    88               88          8b       d8  8b       d8  8888[      88  8PP"""""""        88    8b       d8      88          8b       d8  8b          8888[       `"Y8ba,     88     ,adPPPPP88  88          
88     `8b   88               88          "8a,   ,a8"  "8a,   ,a8"  88`"Yba,   88  "8b,   ,aa        88,   "8a,   ,a8"      88          "8a,   ,a8"  "8a,   ,aa  88`"Yba,   aa    ]8I    88,    88,    ,88  88          
88      `8b  88888888888      88           `"YbbdP"'    `"YbbdP"'   88   `Y8a  88   `"Ybbd8"'        "Y888  `"YbbdP"'       88           `"YbbdP"'    `"Ybbd8"'  88   `Y8a  `"YbbdP"'    "Y888  `"8bbdP"Y8  88          
                                                                                                                                                                                                                        
                                                                                                                                                                                                                        

# Reinforcement Learning: Rookie to Rockstar

A course on Reinforcement Learning that starts from the ground up. The course is a series of (coming) YouTube videos where we build and train RL agents together. The Jupyter notebooks from the lectures are collected inside the `lectures` directory. Each lecture also has exercises listed in the video description. (This may grow into something more comprehensive over time.)

---

### Lecture 1: The spelled-out intro to reinforcement learning: building *Youbandit* 

We implement the simplest possible reinforcement learning agent: the YouTube Thumbnail Bandit. Each arm corresponds to a different thumbnail, and the reward is whether the user clicks. From scratch, we code up action selection, reward tracking, and incremental updates for estimating action values. This lecture focuses on (1) the idea of learning through interaction with an environment, (2) incremental gradient-like updates, (3) the core concepts of exploration vs. exploitation.  

---
### Lecture 2: The spelled-out intro to : building *Personalbandit*

We implement a one-step MDP, also known as a contextual bandit, applied to personalise a YouTube homepage. In follow-up videos, we will expand this into full reinforcement learning agents  operating in multi-step environments. In this lecture, the focus is on (1) introducing states in the RL loop of state → action → reward, (2) build a 2D belief table which opens up having a personalised strategy, (3) introducing and showing how subtle bugs can be hard to spot in RL research, (4) hinting about the need for agents that can generalise.
