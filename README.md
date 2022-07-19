# Simple TF2 DRQN
A super simple implementation of DRQN using TF2 to solve a more challenging version of CartPole where the velocity component of the observation is masked out.

## Train on Google Colab

## MaskedVelocityCartPole
We modify CartPole to make it a partially observed markov decision process (POMDP) by masking out the velocity components of the observation. This means that an agent needs memory inorder to solve this task. Hence, DQN fails on this task while DRQN succeeds.

## Deep Recurrent Q-Networks
[Deep Recurrent Q-Learning for Partially Observable MDPs](https://arxiv.org/pdf/1507.06527.pdf)
