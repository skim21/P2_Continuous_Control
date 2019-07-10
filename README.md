# P2_Continuous_Control


### Continuous Control
This is a part of Udacity project in the course of Deep Reinforcement Learning Nanodegree Program. The original solution from ddpg_pendulum of https://github.com/udacity/deep-reinforcement-learning/tree/master/ddpg-pendulum was used to solve this project.

#### 1. Start the Environment
Run the next code cell to install a few packages. This line will take a few minutes to run!

!pip -q install ./python

#### 2. Environment
This project is to solve the Reacher environment using DDPG (Deep Deterministic Policy Gradient). In Reacher environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible. The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1. The environment contains 20 identical agents, each with its own copy of the environment. The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.

#### 3. Instruction DDPG for Continuous Control Environment
Open Continuous_Control.ipynb, the Step 1 line is run first and the folling lines. The environment definition (env = UnityEnvironment(file_name='/data/Reacher_Linux_NoVis/Reacher.x86_64' , no_graphics=True) was used for the solution on the Udacity workspace. If you want to see if it is run in your local machine, the following line env = UnityEnvironment(file_name='Reacher.app') shall be used. Reacher.app can be downloaded from https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip for Mac OS X, https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip for Linux, https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip for Windows.
