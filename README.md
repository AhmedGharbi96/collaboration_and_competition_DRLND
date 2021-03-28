# collaboration_and_competition_DRLND


## Introduction
This is the final project of the Deep Reinforcement Learning Nanodegree of Udacity.
In this environment, 2 agents control rackets to bounce a ball over a net. If an agent let the ball hit the ground or the ball go out of bounds, the agent receives a reward of -0.01. If an agent hits the ball over the net, it receives a reward of +0.1. Hence, the goal of the two agents is to bounce the ball over the net as long as possible. 

The task is episodic and is considered solved if the agents reach an average score of at least +0.5 over 100 consecutive episodes.

Each agent has its own observations. The observation space for each agent consists of 24 dimensions, which contains observations of the position and velocity of the ball and the racket.

The action space for each agent is continuous and consists of 2 actions: the movements towards and away from the net, and jumping.


## Getting Started
1. Install the necessary packages. 
   Start by creating a conda environment.

```
conda create --name env_name python=3.6
```
2. Install the following packages
 ```
pip install pytorch pytorch
pip install unityagents
pip install mlagents
pip install numpy
pip install matplotlib
```
Download the Reacher unity environment You can download the environment form one of the links below. Select the enviornment that matches your OS
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
3. Clone this repository

## Running the code
After all packages have been installed in the environment you should open Jupyter Notebook using Anaconda, find and open Tennis.iypnb. To run the cells you can simply click on the first one and press Shift + Enter. This can be made through the whole Notebook.
Feel free to play with the hyperparameters during the training to see how it affects the final result. 
