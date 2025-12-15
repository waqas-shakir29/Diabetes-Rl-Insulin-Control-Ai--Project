# Diabetes-Rl-Insulin-Control-Ai--Project
This project implements a Q-Learning based Reinforcement Learning system for diabetes management. A custom environment simulates glucose dynamics influenced by insulin actions, meals, and exercise. The agent learns optimal insulin adjustments to keep blood glucose within a safe range while handling noise and variability.

Diabetes Management using Reinforcement Learning (RL)
Project Overview

Ye project Q-Learning RL agent ka use karta hai jo diabetes ke patient ke glucose levels ko safe range (70-180 mg/dL) me maintain karta hai. Agent actions le sakta hai: increase, decrease, keep.

Features

Simulates glucose response with carbs and exercise

Learns optimal insulin control policy using Q-Learning

Visualizes glucose levels during training and testing

How to Run

Open Diabetes_RL.ipynb in Jupyter Notebook

Run cells sequentially

Plots show glucose trends and safe range

Dependencies
pip install numpy matplotlib

Notes

Training: 500 episodes, 20 time steps per episode

Testing: learned policy without exploration
