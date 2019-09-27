# The solution for the Unity Banana environment (project 1 - Navigation)


(The code is based on materials from Udacity Deep Reinforcement Learning Nanodegree Program.)

## Project Details
This project will train an agent to navigate (and collect bananas!) in a large, square world.

![Banana-gif](https://github.com/RMiftakhov/NavigationProject-drlnd/blob/master/banana-gif.gif)

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* 0 - move forward
* 1 - move backward
* 2 - turn left
* 3 - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started
Download the Unity environment from one of the links below.
* [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
* [Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
* [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
* [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

In order to train the model or inference the computed weights, the following python packages need to be installed:
* *pytorch*
* *unityagents*
* *numpy*
* *matplotlib* 
* *pandas*

## Instructions
Follow the instructions in `Navigation.ipynb` to get started to train the agent.

## Approach

1. Evaluate the state and action space.
2. Establish baseline using a random action policy.
3. Implement learning algorithm.
4. Run experiments to measure agent performance.
5. Select best performing agent.

_Details explanation is provided in `report.pdf` file._

