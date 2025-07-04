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
