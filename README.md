# Cryptocurrency Clustering Analysis

This repository contains the Jupyter notebook `Crypto_Clustering.ipynb` which demonstrates the application of K-means clustering and Principal Component Analysis (PCA) to classify cryptocurrencies based on their price changes over various timeframes. This analysis aims to identify patterns and groups within cryptocurrency price fluctuations to aid in investment and trading decisions.

## Prerequisites

Before you run the notebook, ensure you have the following installed:
- Python 3.8 or later
- Jupyter Notebook or JupyterLab

Additionally, the following Python libraries are required:
- pandas
- numpy
- matplotlib
- sklearn

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Running the Notebook

To run the notebook:
1. Clone this repository to your local machine using:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the repository directory:
   ```bash
   cd <repository-name>
   ```
3. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```
   or
   ```bash
   jupyter lab
   ```
4. Open the `Crypto_Clustering.ipynb` file in the Jupyter interface.
5. Run the cells sequentially to see the analysis process from data loading and preprocessing to clustering and visualization.

## Notebook Sections

1. **Data Preparation**: Load and preprocess cryptocurrency market data.
2. **Scaling the Data**: Normalize the data features using `StandardScaler`.
3. **Finding the Best K-Value**: Apply the elbow method to determine the optimal number of clusters.
4. **K-Means Clustering**: Cluster cryptocurrencies based on their scaled price changes.
5. **Principal Component Analysis**: Reduce dimensionality to visualize clusters.
6. **Cluster Analysis with PCA**: Re-cluster using the principal components and analyze the results.
7. **Feature Influence**: Examine the influence of original features on the principal components.

## References
Based on starter files and data provided as part of OSU-VIRT-AI-PT-02-2024-U-LOLC-MTTH (OSU AI Bootcamp) for Module 11 Challenge. Remaining code based on code examples provided as part of the course.

