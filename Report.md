# Report
## Algorithm
In this project, the Deep Q-Learning algorithm are utilized to solve the game of navigating in a space. Specifically, this implementation employs the fixed Q-targets (using soft updates) and experience replay technique. 

Furthermore, my implementation provides two options for updating Q-target: update directly and update using double Q networks (DQN)
### QNetwork architecture
The model used in this implementation has the following architecture:

- Linear(state_size, 64)
- ReLU()
- Linear(64, 64)
- ReLU()
- Linear(64, action_size)

### Hyperparameters
| Hyperparameter                      | Value |
| ----------------------------------- | ----- |
| Replay buffer size                  | 1e5   |
| Batch size                          | 64    |
| $\gamma$ (discount factor)          | 0.99  |
| Update interval                     | 4     |
| Number of episodes                  | 500   |
| $\tau$                              | 1e-3  |
| Learning rate                       | 5e-4  |
| Max number of timesteps per episode | 1000  |
| Epsilon start                       | 1.0   |
| Epsilon minimum                     | 0.1   |
| Epsilon decay                       | 0.995 |
## Results

## Futher improvements
Deep Q-learning improvements
- Prioritized experience replay
- Dueling DQN
- Rainbow