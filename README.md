# 🛍️ Customer Segmentation using K-Means Clustering
# 📌 Project Overview

This project is part of my Machine Learning Internship at SkillCraft Technologies.
The objective is to apply K-Means Clustering on a retail store dataset to segment customers into distinct groups based on their spending habits and income levels.

Customer segmentation helps businesses:

Understand different types of customers.

Build targeted marketing strategies.

Improve customer satisfaction and sales.

# 📂 Dataset

The dataset used is Mall_Customers.csv, which contains:

CustomerID → Unique identifier for each customer.

Gender → Male/Female.

Age → Customer’s age.

Annual Income (k$) → Annual income of customer.

Spending Score (1–100) → Score assigned based on spending behavior.

# 🔑 Project Workflow

# Data Loading & Exploration

Loaded dataset and explored features.

Checked data distribution.

# Feature Selection

Selected relevant features (Annual Income & Spending Score) for clustering.

# Choosing Optimal Clusters

Used Elbow Method to find the best number of clusters (K=5).

# Applying K-Means Algorithm

Applied K-Means clustering.

Assigned cluster labels to customers.

# Visualization

Plotted customer groups with distinct colors.

Interpreted segments (e.g., High Income – High Spending, Low Income – Low Spending, etc.).

# 📊 Tools & Libraries Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

# 🚀 Results

Identified 5 distinct customer groups based on income and spending patterns.

Clear segmentation helps businesses target each group effectively.

Visual clusters provide insights into customer behavior.

# 📌 Future Enhancements

Use more features (e.g., Age, Gender) for multi-dimensional clustering.

Try other clustering algorithms (Hierarchical, DBSCAN).

Deploy the model as a business dashboard.
