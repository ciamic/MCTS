# MCTS
 Implementation of a Monte Carlo Tree Search algorithm
 
## Introduction
This repo contains: 
- an implementation of a MCTS algorithm 
- an agent that uses the MCTS to play an openAI gym game (CartPole-v0)

### Project details

The code has been adapted from [Udacity Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893 "Udacity Deep Reinforcement Learning Nanodegree").
The MCTS implementation follows the explanation [Monte Carlo Tree Search](https://www.youtube.com/watch?v=UXW2yZndl7U "here").

This is an implementation of a an agent that uses a vanilla implementation of the MCTS algorithm in order to play the openAI gym game of CartPole.

### Getting Started

Execute the code in the notebook to see the agent in action! 

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name MCTS python=3.6
	source activate MCTS
	```
	- __Windows__: 
	```bash
	conda create --name MCTS python=3.6 
	activate MCTS
	```

3. Clone the repository, and then, install the required packages (see requirements).
```bash
git clone https://github.com/ciamic/MCTS.git
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `MCTS` environment.  
```bash
python -m ipykernel install --user --name MCTS --display-name "MCTS"
```

5. Before running code in a notebook, change the kernel to match the `MCTS` environment by using the drop-down contextual `Kernel` menu. 

### Requirements

- `Python 3`
- `numpy`
- `matplotlib`
