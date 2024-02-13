# Crypto Clustering: A Unsupervised Learning Case Study
This project aims to cluster cryptocurrencies based on their market data to identify patterns and group similar cryptocurrencies together. Using a Jupyter notebook, Crypto_Clustering.ipynb, we explore and analyze cryptocurrency market data to perform clustering.
<div align="center">
    <img src="https://github.com/Xthe23/CryptoClustering/blob/main/Resources/img1.png">
    <img src="https://github.com/Xthe23/CryptoClustering/blob/main/Resources/img2.png">
</div>


## Overview
The notebook includes the following key steps:

- Data Preparation: The data is loaded into a Pandas DataFrame from Resources/crypto_market_data.csv, normalized using StandardScaler, and then explored to understand its structure and content.

- Clustering with K-Means: We use the K-Means clustering algorithm to group cryptocurrencies based on their market data. The optimal number of clusters (k) is determined using the Elbow Method.

- Principal Component Analysis (PCA): To reduce dimensionality and improve clustering performance, PCA is applied to the data. This step helps in visualizing the data in lower dimensions while retaining most of the variance.

- Cluster Analysis: The cryptocurrencies are clustered using both the original and PCA-transformed data. The results are visualized to compare the effectiveness of clustering before and after PCA.

- Visualization: Various plots, including line plots and scatter plots, are used to visualize the data, the Elbow Curve (to find the optimal k), and the clustering results.

# Key Findings
- The Elbow Method suggests that the optimal number of clusters for the K-Means algorithm is 3 based on the original data and 4 based on the PCA-transformed data.

- PCA transformation reveals different clustering structures, suggesting that dimensionality reduction can alter the distribution of data points and potentially unveil more nuanced clustering patterns.

- Visual comparison of clustering results with and without PCA shows the impact of dimensionality reduction on the clarity and separation of clusters.

## Technologies Used
- Python
- Pandas
- scikit-learn (for K-Means clustering and PCA)
- hvPlot for visualization

#### How to Use
- Clone the repository.
- Ensure you have Jupyter notebook installed or use Google Colab to open the .ipynb file.
- Install the required Python packages: pandas, scikit-learn, and hvplot.
- Run the notebook cells sequentially to reproduce the analysis and view the clustering results
