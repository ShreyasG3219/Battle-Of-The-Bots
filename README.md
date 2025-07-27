# Battle of the Bots

**SOC-2025**  
Mentored by **Sandeep Reddy Nallamilli** and **Yash Sabale**

This repository contains weekly modules, exercises, and learning resources for the SOC Project Battle Of Bots.

## Setup Instructions

To set up the project environment:

### 1. Create and activate a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate  
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

## Weekly Tasks

### [Week 0](./Week0/)
**Topic:** PyTorch Basics  
**Focus:**
- Understanding How `PyTorch` Works and Learning about important module and methods like `torch.vision`, `torch.utils.data,`torch.optim` in PyTorch package
- Manual and `nn.Sequential` neural network implementation in PyTorch
- Introduction to `backpropagation` , Different Type of `Loss Functions` , `Optimizations` and Training Loops
- Implementing A Neural Network from Scratch to check understanding regarding Backpropagation
- Introduction to `CNN-Convolutional Neural Networks`
- Implemention of Neural Networks on `MNIST Dataset` and `CIFAR-100 Dataset`

### [Week 1](./Week1/)
**Topic:** MultiArmedBandits and Q Learning  
**Focus:**
- Basics Of Reinforcement Learning - Introduction , `Multi Armed Badits Probelms` , `Markov Decision Process` , `Dynamic Programming` , `Monte Carlo Methods` , `Temproal Difference Learning` , `SARSA Algorithm` and `Q-Learning` 
- `Epsilon Greedy` (exploration vs exploitation) and `Upper confidence bounds` for Multi Armed Bandits Problem
- Q Learning and expected rewards stored in tabulature Method
- Implemention of Q Learning on `Frozen Lake Environment` - Slippery and Non Slippery and `Taxi` Environment

### [Week 2](./Week2/)
**Topic:** Deep Q Networks  
**Focus:**
- Learning how Q Learning fails on large state spaces and how to represent them
- Implementing `Deep Q Learning` with a `Experience Relay Buffer` and `Target Q-Network`
- Creating reward functions for different environments
- Implementation on `CartPole-v1` Environment and a custom defined `ChaseEscape` Environment

### [Week 3](./Week3/)
**Topic:** Double Deep Q Networks  
**Focus:**
- Understanding reason behind `instability` in training in Deep Q Netwroks
- Why `DQN's` lead to `over-estimation` of Q-Values
- Learning `DDQN's-Double Deep Q Networks` and Understanding how it stabilizes training and reduces overestimation
- Implementation of DDQN on `ChaseEscape` Environment 
- `Improving Performance` of `ChaseEscape` Agent using `DDQN` 

### [Week 4](./Week4/)
**Topic:** Policy Gradient Method  
**Focus:**
- Understanding difference between `Value-Based Learning` and `Policy Based Learning`
- Understanding `Policy Gradient Method`
- Learning and Implementing `REINFORCE` `Policy Gradient Method`
- Training on `CartPole-v1` environment 
- Understanding Why `REINFORCE` doesn't work on large action spaces environments
- Understanding `Variance` related problem in Policy Gradient Method
