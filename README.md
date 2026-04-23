# Customer Segmentation using PCA & K-Means

## 📌 Project Overview

This project analyzes customer purchasing behavior using transactional e-commerce data to identify meaningful customer segments.

The goal is to transform raw transaction-level data into customer-level behavioral insights and support business decision-making such as targeted marketing, retention, and pricing strategies.

---

## 📊 Dataset

* Brazilian Olist E-commerce dataset (Kaggle)
* ~100K orders, ~90K customers
* Multiple relational tables (orders, customers, payments, items)

---

## ⚙️ Tech Stack

* Python (pandas, numpy, scikit-learn)
* SQL (data merging & preprocessing)
* PCA (dimensionality reduction)
* K-Means (clustering)

---

## 🔄 Workflow

```text
Raw Transaction Data
        ↓
Data Cleaning & Preprocessing
        ↓
Feature Engineering (Customer-level metrics)
        ↓
Log Transformation & Scaling
        ↓
PCA (Dimensionality Reduction)
        ↓
K-Means Clustering
        ↓
Customer Segmentation & Business Insights
```

---

## 🧠 Feature Engineering

Created customer-level behavioral features including:

* Total orders
* Total spending
* Average order value
* Recency (days since last purchase)
* Customer lifetime
* Average items per order

---

## 📈 Modeling Approach

### PCA

* Reduced feature dimensionality
* Retained ~87% of variance with 4 components

### K-Means Clustering

* Used elbow method and silhouette score to determine optimal clusters
* Selected **K = 3** based on balance between interpretability and performance

---

## 📊 Results

Identified 3 key customer segments:

* **Low-Engagement Customers (60%)**
  Low purchase frequency and low spending

* **Moderate-Value Customers (37%)**
  Higher spending but infrequent purchases

* **High-Value Customers (2%)**
  Repeat buyers with higher lifetime value

---

## 💡 Business Insights

* High-value customers → retention & loyalty programs
* Moderate customers → upsell opportunities
* Low-engagement customers → re-engagement campaigns

These insights can support pricing strategy, marketing targeting, and customer lifecycle management.

---

## 🚀 Key Takeaways

* Built end-to-end segmentation pipeline from raw transactional data
* Transformed relational data into meaningful customer-level insights
* Combined statistical methods with business interpretation

---

## 🔧 Future Improvements

* Incorporate product categories and customer demographics
* Try alternative clustering methods (DBSCAN, hierarchical clustering)
* Evaluate impact of segmentation on business KPIs

---

## 👤 Author

Holly Chen
