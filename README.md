# RLCard: A Toolkit for Reinforcement Learning in Card Games
<img width="500" src="https://dczha.com/files/rlcard/logo.jpg" alt="Logo" />


[![PyPI version](https://badge.fury.io/py/rlcard.svg)](https://badge.fury.io/py/rlcard)

RLCard is a toolkit for Reinforcement Learning (RL) in card games. It supports multiple card environments with easy-to-use interfaces for implementing various reinforcement learning and searching algorithms. The goal of RLCard is to bridge reinforcement learning and imperfect information games. RLCard is developed by [DATA Lab](http://faculty.cs.tamu.edu/xiahu/) at Rice and Texas A&M University, and community contributors.

*   Official Website: [https://www.rlcard.org](https://www.rlcard.org)
*   Tutorial in Jupyter Notebook: [https://github.com/datamllab/rlcard-tutorial](https://github.com/datamllab/rlcard-tutorial)

## Installation
Make sure that you have **Python 3.6+** and **pip** installed. We recommend installing the stable version of `rlcard` with `pip`:

```
pip3 install rlcard
```
The default installation will only include the card environments. To use PyTorch implementation of the training algorithms, run
```
pip3 install rlcard[torch]
```

Then install with
```
cd rlcard
pip3 install -e .
pip3 install -e .[torch]
```

We also provide [**conda** installation method](https://anaconda.org/toubun/rlcard):

```
conda install -c toubun rlcard
```

Conda installation only provides the card environments, you need to manually install Pytorch on your demands.
## Training Examples
run 120220420_DQN/DoubleDQN/DuelingDQN.ipynb

## Inference Examples
run 120220420_inference.ipynb
Modify below codes in 120220420_inference.ipynb
DQN/Double DQN/Dueling DQN
```
model = torch.load('logs/dqn_model.pt') #logs/double_dqn_model.pt, logs/dueling_dqn_model.pt
```

