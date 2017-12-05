# tianshou
Tianshou(天授) is a reinforcement learning platform. The following image illustrate its architecture.

<img src="https://github.com/sproblvem/tianshou/blob/master/docs/figures/tianshou_architecture.png" height="200"/>

## agent
&nbsp;&nbsp;&nbsp;&nbsp;Examples

&nbsp;&nbsp;&nbsp;&nbsp;Self-play Framework

## core

### Model
&nbsp;&nbsp;&nbsp;&nbsp;DQN, Policy-Value Network of AlphaGo Zero, PPO-specific, TROP-specific

### Algorithm

#### Loss design
&nbsp;&nbsp;&nbsp;&nbsp;Actor-Critic (Variations), DQN (Variations), DDPG, TRPO, PPO

#### Optimization method
&nbsp;&nbsp;&nbsp;&nbsp;SGD, ADAM, TRPO, natural gradient, etc.

### Planning
&nbsp;&nbsp;&nbsp;&nbsp;MCTS

## data
&nbsp;&nbsp;&nbsp;&nbsp;Training style - Monte Carlo or Temporal Difference

&nbsp;&nbsp;&nbsp;&nbsp;Reward Reshaping/ Advantage Estimation Function

&nbsp;&nbsp;&nbsp;&nbsp;Importance weight

&nbsp;&nbsp;&nbsp;&nbsp;Multithread Read/Write

## environment
&nbsp;&nbsp;&nbsp;&nbsp;DQN repeat frames etc.

## simulator
&nbsp;&nbsp;&nbsp;&nbsp;Go, Othello/Reversi, Warzone

<img src="https://github.com/sproblvem/tianshou/blob/master/docs/figures/go.png" height="150"/> <img src="https://github.com/sproblvem/tianshou/blob/master/docs/figures/reversi.jpg" height="150"/> <img src="https://github.com/sproblvem/tianshou/blob/master/docs/figures/warzone.jpg" height="150"/>

## TODO
Search based method parallel.
