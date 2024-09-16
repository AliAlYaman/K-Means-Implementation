# K-Means-Implementation from scratch

This repository contains an implementation of the K-Means clustering algorithm from scratch in Python. The K-Means algorithm is a popular unsupervised machine learning method used for partitioning a dataset into `K` distinct clusters based on their similarity. This project demonstrates how to build and apply the K-Means algorithm.

## Table of Contents
- [Overview](#overview)
- [Steps of K-Means](#steps-of-k-means)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Overview

K-Means is a clustering algorithm that works by grouping data points into `K` clusters based on feature similarity. The algorithm aims to minimize the sum of squared distances between data points and their corresponding cluster centroids.

This implementation of K-Means is written from scratch, demonstrating how to:
- Initialize centroids
- Assign data points to the nearest centroid
- Recompute the centroids based on current cluster assignments
- Iterate until convergence

## Steps of K-Means

The K-Means algorithm follows these key steps:

1. **Choose the number of clusters (`K`)**:
   - Select the number of clusters you want the data to be grouped into. The value of `K` is predefined before running the algorithm.

2. **Initialize centroids**:
   - Randomly select `K` data points from the dataset as the initial centroids (cluster centers).

3. **Assign points to the nearest centroid**:
   - For each data point, calculate its distance from each centroid and assign it to the nearest centroid. This step forms `K` clusters.

4. **Recompute the centroids**:
   - For each cluster, compute the new centroid by taking the mean of all the data points assigned to that cluster.

5. **Repeat until convergence**:
   - Repeat steps 3 and 4 until the centroids do not change significantly or a predefined number of iterations is reached. This indicates that the algorithm has converged.

6. **Final clusters**:
   - Once convergence is achieved, the final clusters are formed, and each data point is assigned to its corresponding cluster.

## Requirements

- Python 3.x
- NumPy (for handling numerical operations)
- Matplotlib (optional, for visualizing the clusters)

## Installation

To install the required dependencies, run:

```bash
pip install numpy matplotlib
```

## Usage

To use this K-Means implementation, you need to create your python environment:

```bash
python -m venv <name-of-your-env>
```
or
```bash
python3 -m venv <name-of-your-env>
```
Note that you need to install pip/pip3 before

Now run the jupyter files.

