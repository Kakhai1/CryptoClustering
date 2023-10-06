# Cryptocurrency Clustering and Analysis
## Overview

This GitHub repository contains a project focused on clustering and analyzing cryptocurrencies using machine learning techniques. The project aims to provide insights into the relationships and patterns among various cryptocurrencies based on their market data. It involves data preprocessing, dimensionality reduction using PCA (Principal Component Analysis), and clustering using K-Means.

## Project Highlights

- **Data Loading and Preprocessing**: The project begins with loading market data from a CSV file (`crypto_market_data.csv`) into a DataFrame and performing data preprocessing tasks to prepare it for analysis.

- **Standardization**: The data is standardized using the StandardScaler module from scikit-learn to ensure that features are on the same scale.

- **Dimensionality Reduction**: Principal Component Analysis (PCA) is employed to reduce the dimensionality of the dataset and capture its key patterns and relationships.

- **Clustering Analysis**: K-Means clustering is applied to group cryptocurrencies into clusters based on their features. The optimal number of clusters is determined using the Elbow method for both the original and PCA-transformed data.

- **Visualization**: The project includes interactive visualizations using `hvplot` to showcase scatter plots, elbow curves, and comparisons between original and PCA data.
