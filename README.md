# Readme

## Project Details

This project is a solution to the Udacity Deep Reinforcement Learning nanodegree project 3 (https://github.com/udacity/deep-reinforcement-learning/tree/master/p3_collab-compet). 

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
This yields a single score for each episode.
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

My implementation of an agent solving the environment is found in in `ddpg_agent.py` and `model.py` in the root directory.

It is heavily based on the DDPG bipedal walker example from the respective Udacity nanodegree Github repository  (https://github.com/udacity/deep-reinforcement-learning/tree/master/ddpg-bipedal).


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
