#  SmartCart : E-Commerce Customer Segmentation System

##  Overview

This project builds an intelligent customer segmentation system for **SmartCart**, an e-commerce platform, using **Unsupervised Machine Learning**. By analyzing customer demographics, purchasing behavior, and engagement data, the system identifies distinct customer groups to support personalized marketing and customer retention strategies.

---

##  Problem Statement

SmartCart currently uses the same marketing strategy for all customers, making it difficult to identify high-value customers and improve engagement. The goal of this project is to discover meaningful customer segments using clustering techniques and provide actionable business insights.

---

##  Dataset

* **Records:** 2,240 customers
* **Features:** 22
* **Data Includes:**

  * Customer demographics
  * Purchase behavior
  * Website activity
  * Campaign response
  * Customer engagement

---

##  Workflow

* Data Cleaning & Missing Value Handling
* Feature Engineering
* One-Hot Encoding
* Feature Scaling
* Principal Component Analysis (PCA)
* Cluster Evaluation (Elbow Method & Silhouette Score)
* Model Comparison
* Customer Segmentation & Profiling

---

##  Algorithms Used

* K-Means Clustering
* Agglomerative Hierarchical Clustering (Ward Linkage)
* DBSCAN

After benchmarking all three algorithms, **Agglomerative Hierarchical Clustering** was selected as the final model due to its superior cluster separation and interpretability.

---

##  Customer Segments

| Cluster      | Customer Type                     |
| ------------ | --------------------------------- |
| 🟣 Cluster 0 | Family Shoppers                   |
| 🔵 Cluster 1 | Premium Customers                 |
| 🔴 Cluster 2 | Single Parents / Digital Browsers |
| 🟢 Cluster 3 | High-Value Singles                |

---

##  Key Insights

* Income is the strongest factor influencing customer spending.
* High-income customers contribute the highest revenue.
* Families with more children are more discount-driven.
* Frequent website visits do not always result in higher purchases.
* Four distinct customer personas enable targeted marketing strategies.

---

##  Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Kneed

---

##  Results

The final model successfully segmented customers into **four meaningful groups**, helping SmartCart better understand customer behavior and enabling data-driven marketing, personalized recommendations, and improved customer retention.

---

##  Future Scope

* Deploy the model using Streamlit or Flask
* Integrate with a recommendation system
* Perform real-time customer segmentation
* Build an interactive analytics dashboard
