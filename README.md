# Cart-Pole-RL-Agent

This project implements a Deep Q-Network (DQN) agent trained to solve the classic CartPole-v1 environment from OpenAI Gym. The agent learns to balance a pole on a moving cart by interacting with the environment, collecting experience, and improving its policy over time.

The implementation includes:

- A neural network based Q-function approximator

- Experience Replay Buffer for stable training

- Target Network updates to reduce Q-value oscillation

- Training Statistics

Across training, the agent improves from near random performance to achieving high, stable episode rewards, demonstrating successful learning and control.
