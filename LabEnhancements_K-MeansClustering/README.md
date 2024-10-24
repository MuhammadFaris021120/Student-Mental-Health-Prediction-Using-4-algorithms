# Lab Enhancemnet K-Means ReadMe

## Overview

This repository provides an in-depth exploration of K-Means clustering, a widely used unsupervised learning algorithm, and introduces the concept of constrained K-Means. The ReadMe file serves as a comprehensive guide to understanding the repository's contents and offers insights into the clustering methods discussed, including a comparison with DBSCAN.


## Team Members

| Student Name                    | Student ID | Contribution                                           |
|---------------------------------|------------|--------------------------------------------------------|
| Muhammad Faris Bin Shaik Mohamed| 1181202007 | Enhanced the entire lab for K-Means Clustering         |
| Muhammad Irfan Bin Nasir Khan   | 1191101753 | Enhanced lab for PCA.                                  |
| Muhammad Irfan Bin Nasir Khan   | 1191101753 | Enhanced lab for Logistic Regression.                  |
| Muhammad Yazid Bin Yunos        | 1191202305 | Enhanced lab for Linear Regression.                    |

## Contents

1. Understanding K-Means Clustering
- Overview of the K-Means algorithm.
- Key tasks: Identifying optimal centers (centroids) and assigning data points to their nearest center.
- Visual representation of the clustering process.

2. Implementing K-Means with Scikit-Learn and Dummy Data
- Importing necessary libraries.
- Creating dummy data based on height and weight.
- Selecting the number of clusters (K).
- Visualizing the clustering process.
- Using the Elbow Method to determine the optimal number of clusters.
- Applying Silhouette Analysis to evaluate cluster quality.

3. Constrained K-Means: Managing Group Size
- Introduction to Constrained K-Means.
- Practical example: Assigning students to classrooms.
- Generating synthetic data with distinct clusters.
- Implementing the KMeansConstrained model.
- Visualizing the results of constrained K-Means clustering.

4. Advanced Techniques for Evaluating Clustering Performance
- Comparing K-Means and DBSCAN on crescent-shaped data.
- Visualizing and interpreting the results.
- Choosing the optimal clustering method for the dataset.

## How to Use

1. Downloading the Repository:
   - Click the "Code" button on the GitHub repository page.
   - Select "Download ZIP" from the dropdown.
   - Extract the ZIP file on your local machine.

2. Explore the Code:
   - Open Jupyter notebooks in your preferred environment (e.g., google colab, Jupyter Notebook, JupyterLab).
   - Navigate to the extracted repository and open the relevant notebook.

3. Run Jupyter Notebooks:
   - Read through the code and comments in the notebooks to understand the concepts and implementations.
   - Modify parameters, such as the number of clusters, to observe the impact on clustering results.

4. Experimenting with Constrained K-Means:
   - Adjust parameters such as the number of clusters, minimum size, and maximum size in the constrained K-Means section.
   - Observe how the algorithm optimally partitions the data while adhering to size constraints.

5. Assessing Clustering Performance:
   - Compare K-Means and DBSCAN on crescent-shaped data.
   - Analyze the strengths and weaknesses of each algorithm in various scenarios.

## Dependencies

Ensure you have the following Python libraries installed:

- pandas
- matplotlib
- numpy
- scikit-learn
- k_means_constrained

## Conclusion

Lab Enhancement K-Means ReadMe

This repository offers an in-depth exploration of K-Means clustering, constrained K-Means, and a comparison with DBSCAN. Utilize the provided notebooks to learn, experiment, and grasp the practical applications of these clustering techniques.

