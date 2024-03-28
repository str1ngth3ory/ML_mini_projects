## CS 7641 Assignment 3: Unsupervised Learning and Dimensionality Reduction
The objective of this assignment is to explore two Unsupervised Learning (Clustering) and four Dimensionality Reduction (DR) algorithms and their empirical behavior when applied to the previous datasets from Assignment 1. The two Clustering algorithms are K-Means and Expectation-Maximization (EM, which is implemented as Gaussian Mixture in sklearn). The four Dimensionality Reduction algorithms are Principal Component Analysis (PCA), Independent Component Analysis (ICA), Random Projection (RP), and Isomap. And the two datasets are the Apple Quality and the Wisconsin Diagnostic Breast Cancer (WDBC) datasets. By analyzing the performance of Unsupervised Learning and Dimensionality Reduction algorithms on these datasets, we aim to gain a deeper understanding of their strengths and limitations.

Github link: https://github.gatech.edu/zsang31/cs7641

## Dataset Information
    - Apple Quality (https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality)
    - Breast Cancer Wisconsin Diagnostic (https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

## Prerequisites
The following library are required:
    - numpy
    - pandas
    - matplotlib
    - scikit-learn
    - scipy

And Jupyter Notebook is required.

## How to run
1. Open the corresponding .ipnyb file with Jupyter Notebook.
    - apple.ipynb
    - breast_cancer.ipynb
2. Download the dataset from the above links, and set the path to the dataset by editing the second cell in the Jupyter Notebook file.
3. Run every cell sequentially execpt the cell that commented as \#\#\# SKIP \#\#\#

Reference
1. Silhouette Analysis: https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html
2. sklearn documentation
3. Ed Discussion
