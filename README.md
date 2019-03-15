This project is one of the projects from [Udacity Deep Reinforcement Learning Nano-degree](https://github.com/udacity/deep-reinforcement-learning).

Following is the process and results I have done.

---
# Project Details

![](https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif)

## The environment

For this project, we will work with the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.  

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.


## Solving the environment

**The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes.**

# Getting Started

## Step 1: Clone the Repository

To clone this git repository, put a following commandline.

```
$ git clone https://github.com/jhyun0919/udacity_drlnd_p2.git
```

## Step 2: Download the Unity Environment

For this project, you need to download the Unity Environment from one ot the links below.

* [Linux]()
* [Linux (headliss ver.)]()
* [OSX]()
* [Windows (32-bit)]()
* [Windows (64-bit)]()

After download it, you need to place the file in the root directory of this project repository.

## Step 3: Set virtual environment for this project

The project dependency is listed in [requirements.txt](https://github.com/jhyun0919/udacity_drlnd_p2/blob/master/requirements.txt).  
The dependency can be met with the following command:

```
$ pip install -r requirements.txt
```

# Instructions

You can check out about the description of the implementation & results of the experiment on this project in [Continuous_Control.ipynb]() & [Report.pdf]().

