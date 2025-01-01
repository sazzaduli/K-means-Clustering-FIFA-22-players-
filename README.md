# Project Overview

In this project, I explored FIFA 22 player data using K-means clustering, a simple yet powerful machine-learning technique. Clustering allows us to find patterns in data by grouping similar items together, and K-means is one of the most popular methods for this.

I built a K-means clustering algorithm from scratch using Python and Pandas and compared its performance to the implementation provided by scikit-learn. Using this, I analyzed the dataset to uncover insights about player performance, how they’ve evolved over time, and strategies for building competitive teams.

### Project Steps

- Started by understanding and preprocessing the FIFA dataset
- Wrote pseudocode to plan out the K-means algorithm
- Coded the algorithm from scratch step by step
- Visualized the resulting clusters to see how players were grouped
- Compared my custom implementation to the scikit-learn version for performance and accuracy

# K-means Clustering: A Simple Overview

K-means is a widely used technique in machine learning that helps group similar data points together, a process known as clustering. The goal is to uncover patterns in the data, making it easier to analyze and draw meaningful insights. The beauty of K-means is that it’s an iterative algorithm, meaning it keeps refining the clusters step by step until it reaches the best possible grouping.

To run a k-means clustering:

1. Specify the number of clusters you want (usually referred to as k). This defines how many groups you want the algorithm to identify in the data.
2. Randomly initialize the centroid for each cluster. The centroids represent the centre of each cluster and are initially chosen at random from the data points.
3. Determine which data points belong to which cluster by finding the closest centroid to each data point. Each data point is assigned to the cluster whose centroid is closest to it.
4. Update the centroids based on the geometric mean of all the data points in the cluster. The new centroids are calculated by averaging the positions of the points in each cluster.
5. Run steps 3 and 4 until the centroids stop changing. The process is repeated until the centroids stabilize, with each repetition called an iteration.

![k-means convergence](https://upload.wikimedia.org/wikipedia/commons/e/ea/K-means_convergence.gif)

# About the Dataset

For my project, I’m using a dataset that includes detailed player stats from FIFA 15 to FIFA 22, covering every player in FIFA Career Mode. This dataset is perfect for comparing players across different years, like seeing how Messi and Ronaldo’s stats have evolved and how they align with real-life performance. It also lets me experiment with building competitive teams without overspending, helping me figure out when spending more doesn’t make a significant difference. Additionally, I can track how key player attributes like speed and ball control have changed over time, revealing which traits are becoming more important for top players. Overall, the dataset offers a fascinating way to explore football through data and trends.

# Getting Started

This is what you will need for this project:

- Python 3.8+
- Libraries:
   - Pandas
   - NumPy
   - Scikit-learn
   - Matplotlib
- Dataset: Download the FIFA 22 Complete Player Dataset from 
[Kaggle](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset)

# Code

The code for this project is  [here](https://github.com/sazzaduli/K-means-Clustering-FIFA-22-players-/blob/main/K-means%20Clustering%20(FIFA%2022%20players).ipynb).


