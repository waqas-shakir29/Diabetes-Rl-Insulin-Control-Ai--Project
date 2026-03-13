# Diabetes-Rl-Insulin-Control-Ai--Project
## Diabetes-Rl-Insulin-Control-Ai--Project
* This project implements a **Q-Learning** based Reinforcement Learning system for **diabetes** management. 
* A custom environment simulates glucose dynamics influenced by insulin actions, meals, and exercise. 
* The agent learns optimal insulin adjustments to keep blood glucose within a safe range while handling noise and variability.
# Diabetes Management using Reinforcement Learning (RL) Project Overview
* This project uses a **Q-Learning RL** agent to maintain a **diabetes patient's** glucose levels within a safe range (70–180 mg/dL).
* The agent can take actions: **increase, decrease, or keep.**
# Features
* Simulates glucose response with carbs and exercise.
* Learns optimal insulin control policy using Q-Learning.
* Visualizes glucose levels during training and testing.
# How to Run
* Open Diabetes_RL.ipynb in Jupyter Notebook.
* Run cells sequentially.
* Plots show glucose trends and the safe range.
# Dependencies
pip install numpy matplotlib
# Notes
* Training: 500 episodes, 20 time steps per episode.
* Testing: Learned policy without exploration.
