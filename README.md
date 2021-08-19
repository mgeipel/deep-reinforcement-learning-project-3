# Readme

## Project Details

WORK IN PROGRESS

This project is a solution to the Udacity Deep Reinforcement Learning nanodegree project 1 (https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation). 

The environment's state space is continous and 37-dimensional. The action is discrete with 4 actions.

According to the project spec, the environment is considered solved if the agent is able to receive an average reward (over 100 episodes) of at least 13.

My implementation of an agent solving the environment is found in in `ddpg_agent.py` and `model.py` in the root directory.

 It is heavily based on the exercise code from lesson 2.2 Deep-Q-Learning of the respective Udacity nanodegree  (https://github.com/udacity/deep-reinforcement-learning/tree/master/dqn/solution).



## Getting Started

### Install the dependencies

    pip install -r requirements.txt

### Download the environment

Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

more detailed instructions can be found at https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation.

### Train an agent

`Tennis.ipynb` contains the entry point to training an agent and loading a trained agent for evaluation.

`Report.ipynb` documents the parameters of the double DQN used to train the agent.
