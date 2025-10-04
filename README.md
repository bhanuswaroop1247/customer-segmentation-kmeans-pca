# Project Title

**Market Segmentation Analysis for a Banking Client**

***

## Brief One Line Summary

A data science project to perform market segmentation on a bank's customer dataset using K-Means clustering and dimensionality reduction techniques to enable targeted marketing campaigns.

***

## Overview

This project applies unsupervised machine learning techniques to identify distinct customer groups within a bank's client base. By analyzing patterns in customer transaction and behavior data, the model segments customers into clusters, providing the marketing team with actionable insights to develop tailored advertising strategies and improve campaign effectiveness.

***

## Problem Statement

A bank in New York City wants to move from generic to targeted marketing to enhance customer engagement and sales.The marketing team's primary challenge is to understand the diverse needs of their customers.This project aims to solve this by dividing the bank's customers into at least three distinct groups, allowing for the launch of a focused and efficient ad marketing campaign.

***

## Dataset

The project utilizes a dataset provided by the bank, containing extensive data on their customers over the past six months.

* **Sample features:** `BALANCE`, `PURCHASES`, `CREDIT_LIMIT`, and `TENURE`.
* **Dataset** :This project is based on a proprietary dataset from a private course. The data file (Marketing_data.csv) is included in this repository for reproducibility..

***

## Tools and Technologies

* **Python**, **Pandas** for data cleaning and manipulation
* **scikit-learn** for implementing K-Means clustering and PCA
* **Keras** for building and training autoencoder models
* **Matplotlib** & **Seaborn** for exploratory data analysis (histograms, distplot, KDE plots)
* **Colab Notebook** for the development environment

***

## Methods

**K-Means Clustering:** Applied K-Means, an unsupervised algorithm, to group customers with similar attributes into distinct clusters based on Euclidian distance.
**Elbow Method:** Utilized the "Within Cluster Sum of Squares" (WCSS) to determine the optimal number of clusters (K) for the segmentation model.
**Dimensionality Reduction:** Employed **Principal Component Analysis (PCA)** and **Autoencoders** to reduce the number of features while retaining essential information, aiding in visualization and model performance.
* **Exploratory Data Analysis (EDA):** Performed data visualization to understand the underlying patterns and distributions within the customer dataset.
* **Data Preprocessing:** Cleaned the dataset by handling and filling in missing data points (null elements).

***

## Key Insights

* Unsupervised clustering effectively reveals natural groupings within the customer base without needing pre-existing labels.
* The Elbow Method offers a robust technique for identifying the most meaningful number of customer segments.
* Dimensionality reduction with PCA and Autoencoders is crucial for simplifying complex, high-dimensional data, making it easier to analyze and visualize.

***

## Dashboard/Model/Output

* Python scripts and notebooks that generate customer cluster assignments.
* The final output provides a clear segmentation of the customer base, which can be delivered to the marketing department.
* Visualizations illustrating the defining characteristics and spending habits of each identified customer segment.

***

## How to Run This Project?

To open any notebook from this repository directly in Google Colab:
1.  Copy the notebook's GitHub URL.
2.  Replace `github.com` with `githubtocolab.com` in the URL.
3.  Paste the modified URL into your browser and press Enter; the notebook will open in Colab, ready to execute.

***

## Results & Conclusion

* The K-Means model successfully partitioned the bank's customers into distinct, actionable groups for the marketing team.
* The analysis provides a clear profile for each customer segment, highlighting key behaviors and characteristics.
* This project serves as a practical demonstration of how data science can be leveraged to solve real-world business problems like market segmentation.
