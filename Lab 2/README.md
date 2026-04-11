# Lab 2: Dynamic Programming for GridWorld

## Overview

In this lab, I implemented Dynamic Programming methods to solve a Markov Decision Process (MDP). The goal is to find the optimal value function and policy for an agent moving in a GridWorld environment.

I implemented:
- Value Iteration
- Policy Iteration
- Deterministic and Stochastic GridWorld
- Applied the same methods to FrozenLake (Gymnasium)

The agent learns the best path to reach the goal while minimizing the number of steps.

---

## How to Run the Code

### 1. Clone the repository

```bash
git clone https://github.com/sanad0123/Reinforcement-Learning-MSDS684.git

cd Reinforcement-Learning-MSDS684

pip install -r requirements.txt

jupyter notebook Lab_2.ipynb

```