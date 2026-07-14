# Week 3 — Reinforcement Learning

Part of [Course 3: Unsupervised Learning, Recommenders, Reinforcement Learning](../README.md) — Machine Learning Specialization by Andrew Ng (DeepLearning.AI).

## 📁 Contents

| File | Description |
|---|---|
| `State-action value function example.ipynb` | Exploration of the Q-function and Bellman Equation on a simple grid environment |
| `C3_W3_Reinforcement_Learning_Assignment.ipynb` | Deep Q-Learning to train an agent to land a lunar module 🚀 |

## 🎯 Key concepts

- **Reinforcement Learning** — an agent learns to make decisions by receiving rewards or penalties from its environment, without labeled data
- **State, Action, Reward** — the core components of a Markov Decision Process (MDP)
- **Discount factor (γ)** — controls how much future rewards are valued compared to immediate rewards
- **Q-function** — estimates the total return from taking action a in state s and then acting optimally
- **Bellman Equation** — Q(s,a) = R(s) + γ × max Q(s',a') — the recursive formula for computing Q values
- **Deep Q-Learning (DQN)** — using a neural network to approximate the Q-function for continuous state spaces
- **Epsilon-Greedy Policy** — balancing exploration (random actions) and exploitation (best known action)

## 💡 What I learned

- How to formulate a real-world problem as a Markov Decision Process (state, action, reward, policy)
- The difference between deterministic and stochastic environments (Expected Return)
- How the Bellman Equation recursively defines the value of taking an action in a state
- How Deep Q-Learning transforms a reinforcement learning problem into a supervised learning problem
- How to train a neural network agent to land a lunar module using TensorFlow

## 🛠️ Built with

- Python
- NumPy
- TensorFlow / Keras
- Jupyter Notebook
- OpenAI Gym (Lunar Lander environment)
