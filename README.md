### DRL-Mutli-Agent
This repo is created as a part of [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)

### The Environment
Follow the instructions below to explore the environment on your own machine! You will also learn how to use the Python API to control your agent.

![Environment](https://github.com/vickyskarthik/DRL-Mutli-Agent/blob/master/images/tennis.gif)

## Step 1: Activate the Environment
If you haven't already, please follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up your Python environment. These instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

(For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

## Step 2: Download the Unity Environment
For this project, you will not need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)<br/>
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)<br/>
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)<br/>
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)<br/>
Then, place the file in the p3_collab-compet/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.

(For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)

## Step 3: Explore the Environment
After you have followed the instructions above, open Tennis.ipynb (located in the p3_collab-compet/ folder in the DRLND GitHub repository) and follow the instructions to learn how to use the Python API to control the agent.

Watch the (silent) video below to see what kind of output to expect from the notebook, if everything is working properly!

In the last code cell of the notebook, you'll learn how to design and observe an agent that always selects random actions at each timestep. Your goal in this project is to create an agent that performs much better!
## Initial Observation
![observation](https://github.com/vickyskarthik/DRL-Mutli-Agent/blob/master/images/initial%20observation.png)<br/>

## Neural Network Architecture
![Actor](https://github.com/vickyskarthik/DRL-Mutli-Agent/blob/master/images/Actor.png)<br/>
![Critic](https://github.com/vickyskarthik/DRL-Mutli-Agent/blob/master/images/critic.png)<br/>
## OUTPUT
## Ouput after training
![output](https://github.com/vickyskarthik/DRL-Mutli-Agent/blob/master/images/result.png)<br/>

## Graph of Score Vs Episode
![Graph](https://github.com/vickyskarthik/DRL-Mutli-Agent/blob/master/images/graph.png)<br/>

### IDEAS FOR FUTURE WORK
So far the agent is trained only using MADDPG which can also be implemented using the Distributed Distributional Deterministic Policy Gradients(D4PG) algorithms
The performance can also be improved by usage of prioritized experience buffer instead of replay buffer, using other variations of noise and different model architecture.
Also in this attempt the agent interacted with the environment but the agent can be trained using raw pixels from the environment as input.

### REFERENCE
[1] Ryan Lowe, Yi Wu, Aviv Tamar, Jean Harb, Pieter Abbeel, Igor Mordatch, Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments<br/> 
[2] John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, Oleg Klimov, Proximal Policy Optimization Algorithms<br/>
[3] Juliani, A., Berges, V., Vckay, E., Gao, Y., Henry, H., Mattar, M., Lange, D. (2018). Unity: A General Platform for Intelligent Agents. [arXiv preprint arXiv:1809.02627.](https://github.com/Unity-Technologies/ml-agents)<br/>
[4] R. S. Sutton and A. G. Barto, Introduction to Reinforcement Learning, 2nd ed. Cambridge, MA, USA: MIT Press, 2017<br/>
[5] Deterministic Policy Gradient Algorithms, Silver et al. 2014<br/>
[6]Continuous Control With Deep Reinforcement Learning, Lillicrap et al. 2016
