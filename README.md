
# 🧠 Customer Segmentation Analysis: A Data-Driven Marketing Approach
This project aims to perform customer segmentation using unsupervised machine learning techniques. It presents a complete pipeline from raw financial data to meaningful, business-driven customer profiles. By leveraging dimensionality reduction and clustering algorithms, the analysis enables financial institutions to understand better and serve distinct customer groups.

## 📌 Table of Contents
Overview

Technologies Used

Project Pipeline

Cluster Descriptions

Business Insights

How to Run

Visualizations

References

Author

## 📊 Overview
Customer segmentation helps businesses tailor their marketing strategies based on behavioral patterns. In this project, we:

Preprocessed and cleaned the dataset

Corrected skewness and standardized features

Applied PCA and UMAP for dimensionality reduction

Performed clustering using DBSCAN, K-Means, and GMM

Selected the best-performing model: K-Means + UMAP

Visualized and profiled six distinct customer segments

🛠 Technologies Used
Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)

UMAP, PCA, DBSCAN, K-Means, GMM

Plotly (for interactive visualization)

Jupyter Notebook

## 🔁 Project Pipeline
Data Cleaning

Removed irrelevant features

Filled null values with median

Exploratory Data Analysis

Analyzed key metrics like balance, purchase patterns, and cash advances

Feature Transformation

Skewness reduced from 2.39 to -0.119 using log(x+1) + Box-Cox

Standardized features using StandardScaler

Dimensionality Reduction

Compared PCA and UMAP

UMAP better preserved local/global structure

Clustering

Evaluated DBSCAN, K-Means, GMM

Final model: K-Means with UMAP (Silhouette Score: 0.652)

Visualization & Profiling

Used interactive UMAP plots, pie charts, and bar charts

Named and described each cluster for actionable insights

## 🔍 Cluster Descriptions
Cluster	Name	Description
0	Regular Cash Users	Heavy use of cash advances and balance
1	On-Time Payers	Low balance, high one-off purchases, financially disciplined
2	Cash-Only Withdrawers	High cash advance usage, no purchases
3	Installment Shoppers	Structured payment users, low balance
4	New Cash Drawers	Moderate to high purchases + cash usage
5	Big Spenders	Highest spenders with frequent transactions

## 💡 Business Insights

🎯 Personalized Marketing: Targeted offers like cashback, premium cards, or EMI programs.

📉 Churn Reduction: Engage low-activity segments with education or loyalty rewards.

🧮 Risk Management: Monitor high cash-advance users for early financial stress signs.

💼 Upselling/Cross-Selling: Premium services for financially responsible or high-usage customers
