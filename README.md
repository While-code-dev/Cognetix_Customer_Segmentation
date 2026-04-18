# Customer Segmentation (Clustering)

## Overview
This project applies K-Means Clustering to segment customers into meaningful groups based on purchasing behavior using Annual Income and Spending Score.

The objective is to identify customer groups such as high spenders, budget buyers, and premium customers for business insights and targeted marketing.

## Objective
- Perform customer segmentation using unsupervised machine learning
- Apply K-Means clustering
- Determine optimal clusters using Elbow Method and Silhouette Score
- Visualize customer groups
- Generate cluster-level business insights

## Dataset
Mall Customers Dataset

Source:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

File used:
Mall_Customers.csv

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow
1. Load customer dataset
2. Perform exploratory data analysis
3. Clean data and inspect outliers
4. Select features:
   - Annual Income (k$)
   - Spending Score (1-100)

5. Standardize features
6. Use Elbow Method to identify optimal number of clusters
7. Evaluate clustering using Silhouette Score
8. Apply K-Means Clustering
9. Visualize customer segments
10. Generate cluster summary and insights

## Results
The model segments customers into distinct groups based on income and spending patterns.

Generated outputs include:
- Elbow Method plot
- Silhouette Scores
- Cluster Scatter Plot
- Cluster Summary Table

## Business Insights
Possible customer groups identified:
- High Income High Spending Customers
- High Income Low Spending Customers
- Low Income High Spending Customers
- Low Income Low Spending Customers
- Moderate Income Moderate Spending Customers

## How to Run
1. Install dependencies:
pip install -r requirements.txt

2. Open Jupyter Notebook or Google Colab

3. Run:
customer_segmentation.ipynb

## Project Structure
customer_segmentation/
│── customer_segmentation.ipynb
│── Mall_Customers.csv
│── README.md
│── requirements.txt

## Internship Task
Cognetix Technology Machine Learning Internship

Level-2 Task-1:
Customer Segmentation (Clustering)