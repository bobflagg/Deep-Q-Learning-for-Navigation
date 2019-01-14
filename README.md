# Deep-Q-Learning-for-Navigation
My solution for Project 1 from [Udacity's Deep Reinforcement Learning Nanodegree Program](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893).  I've organized the code into there Python modules, which contain code common to the various implementation given to solve the navigation problem, and four Jupyter notebooks containing increasingly more efficient solutions.

## Python Modules

- **Actor (Policy) Model** [model.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/model.py): implements a simple neural network mapping states to (estimated) action values.
- **RL Agent** [agent.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/dqn_agent.py): defines an abstract agent for deep Q-learning which will be subclassed to provide specific solution agents.
- **Trainer** [trainer.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/trainer.py): implements the training method for deep Q-learning.

## Jupyter Notebooks

1. [Deep Q-Learning for Navigation](https://nbviewer.jupyter.org/github/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/01-Deep-Q-Learning-for-Navigation.ipynb)
2. [Double Deep Q-Learning for Navigation](https://nbviewer.jupyter.org/github/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/02-Double-Deep-Q-Learning-for-Navigation.ipynb)

- [Self Learning AI-Agents Part II: Deep Q-Learning](https://towardsdatascience.com/self-learning-ai-agents-part-ii-deep-q-learning-b5ac60c3f47)
