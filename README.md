# Customer Segmentation with K-Means Clustering

## Overview

This project demonstrates customer segmentation using the K-Means clustering algorithm. The goal is to group customers based on their annual income and spending score to better understand customer behavior and tailor marketing strategies.

## Dataset

The project uses the "Mall_Customers" dataset, which contains information about customer demographics and purchasing behavior. The dataset includes the following features:

* CustomerID: Unique identifier for each customer.
* Gender: Gender of the customer (Male/Female).
* Age: Age of the customer.
* Annual Income (k$): Annual income of the customer in thousands of dollars.
* Spending Score (1-100): Score assigned by the mall based on customer behavior and purchasing patterns.

## Methodology

1. **Data Loading and Preprocessing:** The dataset is loaded into a pandas DataFrame. The 'Annual Income' and 'Spending Score' columns are extracted for clustering.
2. **Determining Optimal Clusters:** The Elbow Method is used to determine the optimal number of clusters based on the Within-Cluster Sum of Squares (WCSS).
3. **K-Means Clustering:** The K-Means algorithm is applied to the data with the chosen number of clusters. Customers are assigned to clusters based on their annual income and spending score.
4. **Visualization:** The clusters are visualized using a scatter plot, with different colors representing different customer segments. Centroids of the clusters are also plotted.
5. **Cluster Analysis:** The characteristics of each cluster are analyzed to understand the customer segments.

## Results

The analysis identifies five distinct customer segments with varying income and spending patterns. These segments can be used to develop targeted marketing campaigns and improve customer engagement.

## Usage

1. **Install Required Libraries:**
2. **Run the Code:** Execute the Python code in the provided Jupyter Notebook or Python script.
3. **View Results:** Observe the cluster visualization and analyze the characteristics of each segment.

## Conclusion

This project showcases the power of K-Means clustering for customer segmentation. By identifying distinct customer groups, businesses can gain insights into customer behavior and optimize their marketing strategies.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.
