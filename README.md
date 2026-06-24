# 🐦 Flappy Bird AI using Deep Q-Network (DQN)

## Overview

This project implements a Deep Q-Network (DQN) agent using PyTorch to learn how to play Flappy Bird through reinforcement learning.

The agent uses:
- Deep Q-Learning (DQN)
- Experience Replay
- Target Network
- Epsilon-Greedy Exploration Strategy

## Project Structure

```
agent.py               # Main training/testing script
dqn.py                 # Deep Q-Network architecture
experience_replay.py   # Replay memory implementation
parameters.yaml        # Hyperparameters
```

## Installation

Install the required packages:

```bash
pip install -r requirements.txt
```

## Train the Agent

```bash
python agent.py --hyperparameters flappybirdv0 --train
```

## Test the Trained Agent

```bash
python agent.py --hyperparameters flappybirdv0
```

## Technologies Used

- Python
- PyTorch
- Gymnasium
- flappy-bird-gymnasium
- YAML

## Future Improvements

- Double DQN
- Prioritized Experience Replay
- Dueling DQN
- Hyperparameter tuning

## Author

Aditya Singh Rathore