# Assignment-3-Reinforcement-Learning-Programming

Overview:
This project implements a Deep Q-Network (DQN) agent to play Pong from the OpenAI Gym Atari environment. The DQN uses a convolutional neural network (CNN) to process stacked grayscale frames and learns Q-values for each action using experience replay and a target network. Hyperparameter experiments on mini-batch size and target network update frequency were conducted to evaluate learning stability.

Installation:

Create a virtual environment: python -m venv dqn_env

Activate the environment:

Windows: dqn_env\Scripts\activate

Linux/Mac: source dqn_env/bin/activate

Install dependencies: pip install -r dqn_requirements.txt

Usage:

Open main.ipynb in Jupyter Notebook or VS Code.

Run cells sequentially: environment setup, frame preprocessing, replay buffer, CNN DQN network, target network and optimizer, training loop, hyperparameter experiments, and plotting metrics.

Hyperparameters:

Mini-batch size: 8 (default), 16 (experiment)

Target network update frequency: 10 (default), 3 (experiment)

Discount factor γ = 0.95

Exploration ε: initial 1.0, decay 0.995, min 0.05

Report:

Includes network architecture, metrics, plots, and observations on hyperparameter changes.

Recommended configuration: Batch size 16, Target network update frequency 10 episodes.
