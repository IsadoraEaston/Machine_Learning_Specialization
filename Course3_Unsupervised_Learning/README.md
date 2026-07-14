# Course 3 — Unsupervised Learning, Recommenders, Reinforcement Learning

Part of the [Machine Learning Specialization](../README.md) by Andrew Ng (DeepLearning.AI / Stanford University).

[![Certificate](https://img.shields.io/badge/Coursera-Certificate-blue)](https://coursera.org/verify/H05W3D1LVH3K)

## 📅 Course Structure

| Week | Topic | Labs |
|---|---|---|
| [Week 1](./Week1/README.md) | Unsupervised Learning | K-means Clustering, Anomaly Detection |
| [Week 2](./Week2/README.md) | Recommender Systems | Collaborative Filtering, Content-Based Filtering |
| [Week 3](./Week3/README.md) | Reinforcement Learning | Q-Function, Deep Q-Learning (Lunar Lander 🚀) |

## 🎯 Key concepts

- **K-means Clustering** — grouping unlabeled data into K clusters using centroid initialization and iterative reassignment
- **Anomaly Detection** — modeling normal data with a Gaussian distribution and flagging points with low probability density
- **Collaborative Filtering** — predicting user preferences based on the ratings of similar users, without needing item features
- **Mean Normalization** — improving predictions for new users by centering ratings around their mean
- **Content-Based Filtering** — recommending items using neural network embeddings of user and item features
- **PCA** — reducing data dimensionality while retaining maximum variance
- **Reinforcement Learning** — training an agent to maximize rewards through trial and error
- **Bellman Equation** — Q(s,a) = R(s) + γ × max Q(s',a')
- **Deep Q-Learning (DQN)** — approximating the Q-function with a neural network for continuous state spaces

## 💡 What I learned

- How unsupervised algorithms find structure in data without labeled examples
- How to build a movie recommender system from scratch using collaborative and content-based filtering
- How neural networks learn user and item embeddings for personalized recommendations
- How to formulate a real-world problem as a Markov Decision Process
- How Deep Q-Learning transforms reinforcement learning into a supervised learning problem
- How to train a neural network agent to land a lunar module 🚀

## 🛠️ Built with

- Python
- NumPy
- TensorFlow / Keras
- Jupyter Notebook
- OpenAI Gym (Lunar Lander environment)

← [Back to Specialization](../README.md)
