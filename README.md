# Crypto Clustering

## Overview
This project utilizes machine learning techniques to cluster cryptocurrencies based on their price change percentages over different time periods. The main goal is to identify groups of cryptocurrencies that exhibit similar price behaviors, which can provide insights for investment strategies or market analysis.

## Structure

- **Clustering Analysis:**
  - Application of K-Means clustering algorithm to group cryptocurrencies based on their price change patterns.
  - Evaluation of clustering performance using techniques like elbow method for optimal K selection and silhouette analysis.

- **Dimensionality Reduction:**
  - Implementation of Principal Component Analysis (PCA) to reduce the dimensionality of data while retaining meaningful variance.
  - Visualization of clustered data in reduced dimensions to explore patterns.

- **Visualization:**
  - Creation of scatter plots and composite plots to visualize clustering results.
  - Use of interactive plotting libraries (like HoloViews and hvPlot) to enhance data exploration.

## Results and Insights
- **Cluster Analysis:**
  - Identification of distinct clusters of cryptocurrencies based on price change behaviors.
  - Interpretation of clusters and their characteristics.

- **Visualization Insights:**
  - Visual comparison of original data points versus PCA-transformed data.
  - Analysis of how dimensionality reduction impacts clustering outcomes.

## Usage
- **Dependencies:**
  - pandas, hvplot, holoviews, sklearn

## Future Enhancements
- **Additional Features:**
  - Incorporation of additional features or data sources for more robust clustering.
  - Exploration of alternative clustering algorithms (e.g., DBSCAN, hierarchical clustering).

- **Visualization Improvements:**
  - Enhancing interactive visualizations for better data exploration.
  - Incorporating user-friendly interfaces for dynamic parameter tuning and cluster exploration.
