Customer Segmentation using K-Means Clustering


Project Overview
This project implements the K-Means clustering algorithm to perform customer segmentation. Customer segmentation is the process of grouping customers based on similar characteristics and behavior. The aim of this project is to understand customer patterns using unsupervised machine learning.
The project is implemented using Python in Google Colab.

Dataset Description
The dataset used in this project is the Mall Customers dataset. It contains information about customers such as Customer ID, Gender, Age, Annual Income, and Spending Score.
For clustering purposes, only numerical features are used:
Age
Annual Income (k$)
Spending Score (1-100)

Customer ID and Gender are not used in clustering because they do not contribute to distance-based grouping.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab
Methodology
First, the dataset was loaded and explored to understand its structure and data types.
Next, relevant numerical features were selected for clustering.
Feature scaling was applied using StandardScaler because K-Means is a distance-based algorithm.
The Elbow Method was used to determine the optimal number of clusters.
After selecting the optimal value, the K-Means algorithm was applied to the scaled data.
Cluster labels were added to the dataset.
Finally, the clusters were visualized using 2D and 3D plots.

Results
The K-Means algorithm successfully grouped customers into different clusters based on age, income, and spending behavior. Each cluster represents a different type of customer group, such as high-income high-spending customers, low-income low-spending customers, and average customers.

These results can help businesses understand customer behavior and improve marketing strategies.

Learning Outcomes
Through this project, I learned the basics of unsupervised machine learning.
I gained a clear understanding of how the K-Means algorithm works.
I learned the importance of feature scaling in clustering algorithms.
I also learned how to visualize and interpret clustering results.


