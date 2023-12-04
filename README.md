# Reinforcement_Learning

1) **SARSA_QLearning** - This project familiarized us with two popular Temporal Difference Learning algorithms, SARSA
and Q-Learning. We implemented these algorithms and ran experiments using them on multiple
gridworld environments. We also learned how to use wandb for making sweeps to get optimal
hyper-parameter configurations. Totally, 32 configurations {2×algorithms, 2×action selection policies(epgreedy, softmax), wind = True/False, start = (0, 4)/(3, 6) and action fail probability p = 1.0/0.7} were analyzed and the best hyper-parameters
for them were found using wandb's grid search.

2) **Actor-Critic** - This project familiarized us with the popular DeepRL techniques of DQNs and Actor-Critic methods. We were also introduced to the OpenAI Gym environments of CartPole-v1, Acrobot-v1, and MountainCar-v0. Reward shaping was also used to promote learning.

3) **SMDP QLearning with options** -  This project familiarized us with the popular Hierarchical RL technique of SMDP Q-learning (with options) and Intra option Q-learning methods and were asked to implement these techniques on a simple taxi domain environment. Custom options were also devised to get improved final policy.
