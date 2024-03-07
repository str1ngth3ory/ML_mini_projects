## CS 7641 Assignment 2: Randomized Optimization
The objective of this assignment is to explore various random search algorithms and their empirical behavior when applied to different optimization problems. The four optimization algorithms under scrutiny are Randomized Hill Climbing(RHC), Simulated Annealing(SA), Genetic Algorithms(GA), and MIMIC. In Part 1, these algorithms are applied to three distinct optimization problems: the Flip-flop problem, the Traveling Salesperson problem (TSP), and the Knapsack problem. In Part 2, the first three algorithms are employed to optimize the weights of a Neural Network Model using the Apple dataset from Assignment 1. By evaluating the performance of these random algorithms across these optimization problems, the goal is to acquire a deeper understanding of their strengths and limitations.

Github link: https://github.gatech.edu/zsang31/cs7641

## Dataset Information
    - Apple Quality (https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality)

## Prerequisites
The following library are required:
    - numpy
    - pandas
    - matplotlib
    - scikit-learn
    - mlrose-hiive

And Jupyter Notebook is required.

## How to run
1. Open the corresponding .ipnyb file with Jupyter Notebook.
    - FlipFlop_rev2.0.ipynb
    - TravelingSalesperson_rev1.0.ipynb
    - Knapsack_rev1.0.ipynb
    - apple.ipynb
2. Open each Jupyter notebook and run every cell sequentially
3. This step is specific to apple.ipynb. Download the dataset from the above links, and set the path to the dataset by editing the second cell in the Jupyter Notebook file.
4. This step is specific to apple.ipynb. Prior to running any cell, edit the file locally: mlrose_hiive/neural/neural_network.py. Add this line to the last line of __init__ constructor: "self.classes_ = [0, 1]" (Refer to Ed Discussion Post #725 for details)
