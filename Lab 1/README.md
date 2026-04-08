# MSDS 684 - Reinforcement Learning
## Lab 1: Multi-Armed Bandit and MDP Foundations

This lab implements the multi-armed bandit problem using ε-greedy and UCB exploration strategies, and explores standard Gymnasium environments (FrozenLake-v1 and Taxi-v3) to study MDP foundations.

---

## Setup

### 1. Clone the repository
```bash
git clone https://github.com/sanad0123/Reinforcement-Learning-MSDS684.git
cd Reinforcement-Learning-MSDS684
```

### 2. Create and activate virtual environment
```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

---

## Running the Code

Open and run `Lab_1.ipynb` in Jupyter:

```bash
jupyter notebook Lab_1.ipynb
```

Run all cells in order using **Kernel → Restart & Run All** to reproduce all results and plots.

The notebook is divided into two parts:
- **Part 1:** Custom 10-arm bandit environment, ε-greedy and UCB agents, experiments and plots
- **Part 2:** FrozenLake-v1 and Taxi-v3 environment inspection, MDP mapping, random policy evaluation

---