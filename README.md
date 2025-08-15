# K-Means

# Mall Customer Segmentation using K-Means Clustering

This project demonstrates unsupervised learning with K-Means Clustering to segment customers based on demographic and behavioral features using the Mall_Customers.csv dataset.

# Objective

Apply K-Means clustering to group mall customers into distinct segments based on their age, income, and spending score. This helps businesses understand different customer profiles for targeted marketing.

# Tools & Libraries

Python

pandas for data manipulation

numpy for numerical operations

matplotlib, seaborn for visualization

scikit-learn for machine learning (KMeans, PCA, preprocessing, metrics)

# Steps Performed

# 1. Data Collection & Preprocessing

Loaded dataset using pandas

Checked for missing values and handled them using dropna() and fillna()

Converted categorical variable Gender into numerical using LabelEncoder

Split data into features (x) and label (y)

# 2. Feature Reduction (PCA)

Applied Principal Component Analysis (PCA) to reduce dimensions from 4D to 2D for visualization


# 3. Finding Optimal Clusters (Elbow Method)

Iterated over K = 2 to 10

Trained KMeans model for each K

Plotted inertia vs K to identify the "elbow" point (optimal number of clusters)

# 4. K-Means Clustering & Visualization

Chose optimal K = 5 (from elbow method)

Trained final KMeans model

Visualized clusters in PCA-reduced 2D space

Displayed centroids of clusters

# 5. Evaluation

Used Silhouette Score to evaluate clustering performance:

Silhouette Score = 0.425


Elbow Curve: Helps identify optimal K

2D Cluster Plot: Shows customer segments in reduced space
