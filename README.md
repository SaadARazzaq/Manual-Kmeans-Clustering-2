# Manual Kmeans Clustering #2

This repository contains an implementation of the K-means clustering algorithm using Python (NumPy and Pandas) and visualization of the clusters using Matplotlib but without using any built-in ML Library for Algo Implementation.

## Introduction

K-means clustering is an unsupervised machine learning algorithm used to partition data into clusters based on similarity. The algorithm works iteratively to assign data points to K clusters and update the cluster centroids until convergence.

This repository provides a Python implementation of the K-means algorithm without using built-in libraries. Additionally, it visualizes the clustering results using a scatter plot, making it easier to understand the data's underlying structure.

## Dataset

The dataset used for clustering is loaded from an Excel file named `Data.csv` with two columns representing the X and Y coordinates. You can place your dataset in this file format with appropriate columns for this implementation.

## K-means Clustering

The K-means clustering algorithm is implemented from scratch without relying on any built-in libraries. The optimal number of clusters is determined using the elbow method, allowing the algorithm to group data points efficiently.

## Visualization

The clusters are visualized using a scatter plot, where each cluster is represented by a different color. The centroids of the clusters are marked with black 'x' markers for easy identification.

## Screenshot

![image](https://github.com/SaadARazzaq/Manual-Kmeans-Clustering-2/assets/123338307/9b134acf-c132-43aa-86d5-47416ff024e4)


## How to Use

1. Clone the repository to your local machine:

2. Ensure you have Python and the required libraries (NumPy, Pandas, and Matplotlib) installed.

3. Place your dataset in an Excel file named `Data.csv` with two columns (X and Y coordinates) in the same directory as the Python script.

4. Update the `max_k` variable in the Python script with the optimal number of clusters found using the elbow method.

5. Run the Python script to perform K-means clustering and visualize the clusters:

    ```python
    python main.py

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib

    ```You can install the required libraries using the following command:
    pip install numpy pandas matplotlib

## Contributing

Contributions to this repository are welcome. If you find any issues or improvements, feel free to create a pull request.

## Contact

For any questions or inquiries, you can reach me at sabdurrazzaq124@gmail.com.
