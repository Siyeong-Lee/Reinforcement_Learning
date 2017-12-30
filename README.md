# Reinforcement Learning
###### OpenAI ?κ²½???μ©?΄λ³΄??κ°ν?μ΅ ?μ 

![Alt text](/readme/Play.gif) 
###### [Breakout / Use DQN(Nature2015)] 
![Alt text](/readme/1x1conv.gif) 
###### [Breakout / Image from the first conv layer(1x1)]
---------------
## 1. Q-Learning / SARSA
* FrozenLake(Gridword)
	* [Deterministic Q-Learning](https://github.com/jcwleo/Reinforcement_Learning/blob/master/FrozenLake/FL_Q-Table.py)
	* [add Exploration & Discounted Factor](https://github.com/jcwleo/Reinforcement_Learning/blob/master/FrozenLake/FL_Q-table_exp%26dis.py)
	* [Stochastic Q-Learning](https://github.com/jcwleo/Reinforcement_Learning/blob/master/FrozenLake/FL_Q-table_Stochastic.py)
* WindyGridWorld
	* [Q-Learning/SARSA](https://github.com/jcwleo/Reinforcement_Learning/blob/master/Windygridworld/Q-learning_sarsa.py)
## 2. Q-Network (just use network)
* [FrozenLake(Gridword)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/FrozenLake/FrozenLake_Q-Network.py)
* [CartPole(Classic Control)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/CartPole/CartPole_Q-Network.py)

## 3. DQN(NIPS2013)
DQN(NIPS2013)? (Experience Replay Memory / CNN) ???¬μ©.
* [CartPole(Classic Control)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/CartPole/CartPole_DQN_NIPS2013.py) - Cartpole κ°μ? κ²½μ°?λ CNN???¬μ©?μ? ?κ³  ?Όμ ?λ³΄λ₯??΅ν΄???μ΅

## 4. DQN(Nature2015)
DQN(Nature2015)? (Experience Replay Memory / Target Network / CNN) ???¬μ©

* [CartPole(Classic Control)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/CartPole/CartPole_DQN_Nature2015.py) - Cartpole κ°μ? κ²½μ°?λ CNN???¬μ©?μ? ?κ³  ?Όμ ?λ³΄λ₯??΅ν΄???μ΅
* [Breakout(atari)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/Breakout/Breakout_DQN_class.py)

## 5. Policy Gradient
* [CartPole(Classic Control)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/CartPole/CartPole_PolicyGradient.py) - Cartpole κ°μ? κ²½μ°?λ CNN???¬μ©?μ? ?κ³  ?Όμ ?λ³΄λ₯??΅ν΄???μ΅
* [Pong(atari)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/Pong/Pong_PolicyGradient.py)
* [Breakout(atari)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/Breakout/Breakout_PolicyGradient.py)

## 6. Advantage Actor Critic
* episodic
	* [CartPole(Classic Control)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/CartPole/CartPole_A2C_episodic.py) - Cartpole κ°μ? κ²½μ°?λ CNN???¬μ©?μ? ?κ³  ?Όμ ?λ³΄λ₯??΅ν΄???μ΅
	* [Pong(atari)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/Pong/Pong_A2C_episodic.py)
* one-step
    *  [CartPole(Classic Control)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/CartPole/Cartpole_A2C_onestep.py) - Cartpole κ°μ? κ²½μ°?λ CNN???¬μ©?μ? ?κ³  ?Όμ ?λ³΄λ₯??΅ν΄???μ΅
* n-step
    * [CartPole(Classic Control)](https://github.com/jcwleo/Reinforcement_Learning/blob/master/CartPole/Cartpole_A2C_nstep.py) - Cartpole κ°μ? κ²½μ°?λ CNN???¬μ©?μ? ?κ³  ?Όμ ?λ³΄λ₯??΅ν΄???μ΅

## 7. PAAC(Parallel Advantage Actor Critic)
* Work In Progress
