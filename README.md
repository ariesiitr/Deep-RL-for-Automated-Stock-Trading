# Deep-RL-for-Automated-Stock-Trading
Deep Reinforcement Learning methods for facilitating Automated Stock Trading.

This project implements a Stock Trading Bot, trained using Deep Reinforcement Learning. Implementation is kept simple, Stable baselines has been used for implementation of RL algorithms.

## Reinforcement Learning

![image](https://user-images.githubusercontent.com/81774578/119201322-47ff7f80-baac-11eb-8eaf-ea2fe437c0e1.png)

Reinforcement learning (RL) is an area of machine learning concerned with how intelligent agents ought to take actions in an environment in order to maximize the notion of cumulative reward.Reinforcement learning is one of three basic machine learning paradigms, alongside supervised learning and unsupervised learning.


## Stable-Baselines

Stable Baselines is a set of improved implementations of Reinforcement Learning (RL) algorithms based on OpenAI Baselines.

![image](https://user-images.githubusercontent.com/81774578/119201254-20a8b280-baac-11eb-8963-ee9868339d9a.png)

![image](https://user-images.githubusercontent.com/81774578/119203250-3f10ad00-bab0-11eb-8534-dc023e814208.png)

![image](https://user-images.githubusercontent.com/81774578/119201750-205ce700-baad-11eb-99ed-034f60d69eeb.png)


## Implementing A2C ALgorithm
**A2C** is a policy gradient algorithm and it is part of the on-policy family. That means that we are learning the value function for one policy while following it, or in other words, we can’t learn the value function by following another policy. We will be using another policy if were using experience replay for example, because by learning from too old data, we use information generated by a policy (ie. the network) slightly different to the current state.

![image](https://user-images.githubusercontent.com/81774578/119203325-649db680-bab0-11eb-8004-c948d560dcc6.png)

On each learning step, we update both the Actor parameter (with policy gradients and advantage value), and the Critic parameter (with minimizing the mean squared error with the Bellman update equation)

## Data
You can download Historical Financial data from www.Marketwatch.com for training. We have used data of Apple and DogeCoin for Training.
