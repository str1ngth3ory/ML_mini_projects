## CS 7641 Assignment 4: Markov Decision Processes
This assignment aims to investigate the efficacy of three Reinforcement Learning techniques in addressing two distinct Markov Decision Processes (MDP) problems: Frozen Lake and Blackjack. The techniques under scrutiny include Value Iteration, Policy Iteration, and the Q-Learning Algorithm (Model-free). Through an analysis of their performance, we seek to demonstrate the strengths and limitations of these approaches, providing valuable insights into their practical applicability.

Github link: https://github.gatech.edu/zsang31/cs7641

## Prerequisites
The following library are required:
    - numpy
    - pandas
    - matplotlib
    - seaborn
    - pygame
    - bettermdptools

And Jupyter Notebook is required.

## How to run
1. Open the corresponding .ipnyb file with Jupyter Notebook.
    - frozen_lake_VI_PI_20x20.ipynb
    - frozen_lake_Q_learning_20x20.ipynb
    - frozen_lake_VI_PI_8x8.ipynb
    - frozen_lake_Q_learning_8x8.ipynb
    - blackjack.ipynb
2. Run every cell sequentially execpt the cell that commented as \#\#\# SKIP \#\#\#
3. This step is unique for frozen_lake_Q_learning. Reward shaping is implemented for frozen_lake_Q_learning.
    - replace /gymnasium/envs/toy_text/frozen_lake.py
    - replace /bettermdptools/utils/test_env.py
    - restart kernel and run from the begining of the file

Reference
1. Ed Discussion
2. https://gymnasium.farama.org/environments/toy_text/frozen_lake/
3. https://gymnasium.farama.org/environments/toy_text/blackjack/
