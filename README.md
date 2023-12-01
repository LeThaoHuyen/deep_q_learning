# Deep Q-Learning
In this project, Deep Q-learning algorithm is used to train an agent to navigate and collect yellow bananas in Unity Banana Collector environment.

In detail, a reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal is to colelct as many yellow bananas as possible and avoid blue bananas.

The state space has a dimension of 37 containing the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

## How to use this repos
#### 1: Clone the DRLND Repository
1.  Clone [the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) from Udacity.
2. Create and activate a new conda environment with Python 3.6.
3. Download the necessary dependencies (PyTorch, Numpy, ML-Agents, etc.) from the DRLND repository from the `deep-reinforcement-learning/python` folder with `pip install .`.

#### 2: Download the Unity Environment
1. Download the environment from one of the links below. You need only select the environment that matches your operating system:
    
    -   Linux:  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    -   Mac OSX:  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    -   Windows (32-bit):  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    -   Windows (64-bit):  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out  [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64)  if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.
    
    (_For AWS_) If you'd like to train the agent on AWS (and have not  [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use  [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip)  to obtain the environment.
