# Crypto_Clustering.ipynb

# Project Name
CryptoClustering Market Analysis 

## Overview
This project involves the clustering of cryptocurrency market behavior using K-Means and Principal Component Analysis (PCA). 
The goal is to uncover patterns in price changes over various time frames and identify natural groupings of cryptocurrencies based on market movements.

## Table of Contents
Required Libraries
Installation
Usage
Data
Analysis
Results
Contributing

## Required Libraries
The project requires the following Python libraries:
- sklearn
- pandas
- hvplot

## Installation
Steps include install sklearn, hvplot, Python, and any dependencies.

## Usage
python cluster_analysis.py

## Data
The dataset crypto_market_data.csv contains historical price change percentages for a range of cryptocurrencies across various time frames.


## Analysis
The analysis consists of the following steps:

Data Preprocessing: Scaling features and handling missing values.
Clustering using K-Means: Finding the optimal number of clusters using the elbow method.
Dimensionality Reduction with PCA: Reducing the feature space to two principal components and reapplying K-Means.
Visualizing Results: Comparing the clustering results from the original data and PCA-transformed data.


## Results
The results section will contain the findings from the K-Means clustering and PCA, including:

The optimal number of clusters identified.
The characteristics of each cluster.
A comparison of cluster quality and interpretability between the original and PCA-transformed datasets.


## Contributing
Individual contributer- Nick Nath


## License
edX Boot Camps LLC
