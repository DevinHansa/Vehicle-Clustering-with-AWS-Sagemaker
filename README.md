# Vehicle Clustering using Unsupervised Learning with AWS Sagemaker

## Overview
This project focuses on clustering vehicles into groups based on their features such as weight, engine size, and horsepower. The aim is to uncover patterns and similarities among vehicles using unsupervised learning techniques, particularly KMeans clustering algorithm, implemented with AWS Sagemaker.

## Dataset
A synthetic dataset for vehicles is generated to simulate specifications like Weight, Engine Size, and Horsepower. The dataset is used for clustering without any labeled data.

## Implementation
The project is implemented in Python using the scikit-learn library within an AWS Sagemaker environment. Below are the main steps:

### 1. Importing Libraries
Necessary libraries including Pandas, NumPy, Matplotlib, and scikit-learn are imported.

### 2. Data Generation
A synthetic dataset for vehicles is generated with randomly assigned specifications.

### 3. Unsupervised Learning with Sagemaker
The unsupervised learning algorithm, particularly KMeans clustering, is executed within the AWS Sagemaker environment. This provides scalability and flexibility for handling large datasets.

### 4. Visualization
The clusters are visualized using a scatter plot. Each point represents a vehicle, plotted based on its weight and horsepower, with different colors indicating different clusters.


## Dependencies
- Python 3
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- AWS Sagemaker
