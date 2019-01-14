# Deep-Q-Learning-for-Navigation
My solutions for Project 1 from [Udacity's Deep Reinforcement Learning Nanodegree Program](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893).  

## Project Details

The goal of the Navigation Project is to train an agent to navigate (and collect bananas!) in a large, square world.
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- [**0**] move forward.
- [**1**] move backward.
- [**2**] turn left.
- [**3**] turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started

If you would like to run this code locally follow the instructions below.

1. Set up your Python environment as described the dependencies section of the [readme](https://github.com/udacity/deep-reinforcement-learning) from the [Deep Reinforcement Learning Nanodegree program](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893). 
2. Clone this repository.
3. Create a directory called "data" at the root of the cloned repository.
4. Select the environment that matches your operating system from the list below:
    - [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - [Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
5. Place the file in the data folder you created above.
6. Unzip (or decompress) the file.

## Instructions

I've organized the code into there Python modules, which contain code common to the various solutions, and four Jupyter notebooks containing increasingly more efficient implementations.

### Python Modules

- [model.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/model.py): implements an actor policy model as a simple neural network.
- [agent.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/dqn_agent.py): defines an abstract RL agent for deep Q-learning which will be subclassed in the specific solutions.
- [trainer.py](https://github.com/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/trainer.py): implements the method used to train the agents.

### Jupyter Notebooks

- [Deep Q-Learning for Navigation](https://nbviewer.jupyter.org/github/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/01-Deep-Q-Learning-for-Navigation.ipynb)
- [Double Deep Q-Learning for Navigation](https://nbviewer.jupyter.org/github/bobflagg/Deep-Q-Learning-for-Navigation/blob/master/02-Double-Deep-Q-Learning-for-Navigation.ipynb)

## Additional Resources

## Additional Resources

- [Self Learning AI-Agents Part II: Deep Q-Learning](https://towardsdatascience.com/self-learning-ai-agents-part-ii-deep-q-learning-b5ac60c3f47)
