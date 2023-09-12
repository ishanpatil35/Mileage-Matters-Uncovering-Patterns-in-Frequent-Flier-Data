# Mileage-Matters-Uncovering-Patterns-in-Frequent-Flier-Data


Project Title: Mileage Matters - Uncovering Patterns in Frequent Flier Data

Project Overview:
The "Mileage Matters" project is an analysis of passenger data from an airline's frequent flier program, with the goal of identifying clusters of passengers with similar characteristics. These clusters can be used for targeted marketing efforts, customized mileage offers, and improving customer satisfaction.

Data Description:
The dataset used in this project, named "EastWestAirlines," contains information on frequent fliers, including details such as mileage history, miles earned with various credit cards, bonus miles, flight transactions, and days since enrollment. The dataset also indicates whether a passenger received an award flight (free flight) or not.

Tools and Libraries Used:

Python
Jupyter Notebook
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Project Workflow:

Data Preprocessing:

Renaming columns for clarity.
Removing duplicate entries.
Checking for missing values (none found).
Data Visualization:

Visualizing data distributions using histograms and boxplots.
Exploring correlations between different features using a heatmap.
Data Normalization and Standardization:

Normalizing data for hierarchical clustering.
Standardizing data for K-Means clustering.
Hierarchical Clustering:

Utilizing hierarchical clustering to discover clusters without specifying the number of clusters in advance.
Exploring different linkage methods (complete, single, average, centroid) to find the optimal clustering solution.
Calculating silhouette scores to evaluate cluster quality.
Assigning cluster labels to passengers.
K-Means Clustering:

Employing K-Means clustering to segment passengers into clusters.
Determining the optimal number of clusters using the elbow method and silhouette scores.
Assigning cluster labels to passengers.
DBSCAN Clustering:

Applying DBSCAN (Density-Based Spatial Clustering of Applications with Noise) to detect noise and clusters.
Determining hyperparameters (eps and min_samples) through a search to maximize silhouette scores.
Assigning cluster labels, including a "noise" category.
Cluster Analysis:

Analyzing the characteristics of each cluster, including average values of different features.
Visualizing cluster-specific insights using bar plots.
Project Results:

The project successfully identifies clusters of frequent fliers with similar characteristics.
Two clustering methods (Hierarchical and K-Means) are used to create clusters with interpretable characteristics.
Insights from the clustering can be used for targeted marketing, loyalty program improvements, and customer satisfaction enhancement.
Conclusion:
The "Mileage Matters" project provides valuable insights for airlines to better understand their frequent flier customer base, tailor marketing strategies, and enhance customer loyalty programs. It is a valuable resource for data analysts and airline industry professionals interested in customer segmentation and personalization.
