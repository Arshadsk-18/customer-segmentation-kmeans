# Customer Segmentation using K-Means

A NumPy-powered customer segmentation project that implements **K-Means clustering from scratch** to group customers based on their demographic and purchasing behavior.

The project focuses on understanding the numerical concepts behind clustering, including **feature standardization, Euclidean distance, broadcasting, vectorization, centroid updates, and similarity analysis** — without using Scikit-learn.

---

## 📌 Project Overview

Customer segmentation is the process of grouping customers with similar characteristics and behaviors.

In this project, customer data is generated using NumPy and analyzed using a custom K-Means implementation. Customers are grouped into **3 segments** based on features such as income, purchase frequency, order value, website visits, and total spending.

The complete workflow is implemented using **Python, NumPy, and Matplotlib**.

---

## 🎯 Objectives

- Analyze customer data using NumPy
- Perform statistical analysis on customer features
- Standardize features before clustering
- Calculate Euclidean distances
- Build a customer-to-customer distance matrix
- Implement K-Means clustering from scratch
- Segment customers into meaningful groups
- Find similar customers using distance-based analysis
- Visualize customer segments and spending patterns
- Extract segment-level insights

---

## 📊 Dataset

The project uses a **synthetically generated dataset containing 30 customers**.

### Features

| Feature | Description |
|---|---|
| Customer ID | Unique identifier for each customer |
| Age | Customer age |
| Annual Income | Annual income |
| Purchase Frequency | Number of purchases |
| Average Order Value | Average value of an order |
| Website Visits | Number of website visits |
| Total Spending | Purchase Frequency × Average Order Value |

---

## 🧠 Project Workflow

```text
Generate Customer Data
        ↓
Data Inspection
        ↓
Statistical Analysis
        ↓
Feature Selection
        ↓
Feature Standardization
        ↓
Euclidean Distance
        ↓
Distance Matrix
        ↓
K-Means Clustering
        ↓
Customer Segmentation
        ↓
Similar Customer Analysis
        ↓
Visualization
        ↓
Segment-Level Insights
