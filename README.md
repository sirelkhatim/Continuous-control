# Continuous-control
## Environment and project information
In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.  I used a single agent to train this environment.

## Installation
In order to install dependencies for this project do the following:
```
git clone https://github.com/udacity/deep-reinforcement-learning.git
cd deep-reinforcement-learning/python
pip install .
```
If you would like to train the agent follow the notebook "Continuous_Control.ipynb". 
## Files
- ddpg_agent.py : implementation of ddpg agent
- model.py: actor and critic neural network implementations
- checkpoint_actor.pth : checkpoint of the actor final model
- checkpoint_critic.pth: checkpoint of the critic final model
- Continuous_Control.ipyng: notebook used to train the ddpg agent

## Acknowledgments
In order to create the code I adapted the ddpg code from alexis cook's github repository 'ddpg-bipedal': https://github.com/udacity/deep-reinforcement-learning/tree/master/ddpg-bipedal
