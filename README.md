# Customer Segmentation using K-Means

## Overview

This project uses the K-Means clustering algorithm to segment customers based on their annual income and spending score.

The goal is to identify groups of customers with similar purchasing behavior so that businesses can better understand their customers and develop targeted marketing strategies.

## Objective

To divide customers into meaningful groups using:

- Annual Income
- Spending Score

The optimal number of clusters is determined using the Elbow Method.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Visual Studio Code

## Dataset

The dataset contains information about mall customers, including:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

For clustering, Annual Income and Spending Score were selected as the primary features.

## Project Workflow

1. Import required libraries
2. Load and inspect the dataset
3. Check for missing values
4. Select relevant features
5. Perform exploratory analysis
6. Determine the optimal number of clusters using the Elbow Method
7. Train the K-Means clustering model
8. Visualize the clusters and their centroids
9. Interpret the customer segments
10. Derive business insights

## Results

K-Means clustering was used to divide customers into **5 segments** based on annual income and spending score.

The clusters represent customers with different combinations of income and spending behavior.

## Business Insights

Customer segmentation can help businesses:

- Identify high-value customers
- Create targeted marketing campaigns
- Develop personalized offers
- Identify customers with high income but low spending
- Improve customer retention strategies