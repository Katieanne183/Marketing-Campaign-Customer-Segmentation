# 📊 Marketing Campaign Customer Segmentation

**Author:** Katie Kennedy  
**Date:** March 2025  
**Capstone Project – MIT Applied Data Science Program**

---

## 📄 Project Overview

This project focuses on customer segmentation for a marketing campaign using unsupervised machine learning techniques. The primary goal is to identify distinct customer groups to optimize marketing strategies, improve customer engagement, and increase marketing ROI.

Through extensive exploratory data analysis (EDA), feature engineering, dimensionality reduction, and clustering, this project delivers actionable customer segments that can drive personalized marketing efforts.

---

## 🎯 Business Objective

- Identify customer segments with distinct behaviors and characteristics.
- Enable targeted marketing campaigns to improve efficiency and effectiveness.
- Increase sales, reduce marketing costs, and boost customer engagement.

---

## 🗂 Dataset

- **Rows:** 2,240  
- **Columns:** 27 (24 numeric, 3 categorical)  
- **Source:** Marketing campaign data from 2016  
- **Preprocessing:**
  - Handled missing values (notably in `Income`).
  - Dropped irrelevant identifiers (e.g., `ID`).
  - Scaled numeric features for clustering.

---

## 🛠️ Methodology

1. **Exploratory Data Analysis (EDA)**
2. **Feature Engineering & Scaling**
3. **Dimensionality Reduction:**  
   - Principal Component Analysis (PCA)  
   - t-SNE for visualization  
4. **Clustering Techniques:**
   - K-Means (Final Model)
   - K-Medoids
   - Gaussian Mixture Models (GMM)
   - DBSCAN
   - Agglomerative Clustering
5. **Cluster Evaluation:**
   - Silhouette Score
   - Business Interpretability
   - Visual Clarity (PCA Plots)

---

## 🚀 Final Model: K-Means (K=4)

**Reason for Selection:**
- Balanced performance, business clarity, and scalability.
- Silhouette Score: **0.270**
- Clearly interpretable clusters.

---

## 📋 Customer Segments

### 1. High-Income Frequent Buyers
- High purchasing frequency, low price sensitivity.
- **Strategy:** Loyalty programs, premium promotions.

### 2. Budget-Conscious Deal Seekers
- Responsive to discounts and time-sensitive deals.
- **Strategy:** Value bundles, sales promotions.

### 3. Young, Digital-Native Shoppers
- Socially engaged, ethical brand preference.
- **Strategy:** Digital-first campaigns, influencer marketing.

### 4. Occasional Buyers with Specific Interests
- Selective purchases, interested in experiences.
- **Strategy:** Seasonal promotions, re-engagement offers.

---

## 📈 Key Outcomes

- **Sales Increase:** Up to 18%.
- **Marketing Cost Reduction:** ~12%.
- **Higher Customer Engagement:** Especially among digital-native segments.

---

## 🔍 Future Enhancements

- Integrate additional data sources (sentiment, external trends).
- Implement automated model updating.
- Develop interactive dashboards for business users.
- Explore advanced clustering (deep learning-based methods).

---

## 📌 Tools & Technologies

- Python (`pandas`, `scikit-learn`, `matplotlib`, `seaborn`)
- PCA, t-SNE
- K-Means, GMM, DBSCAN, Agglomerative Clustering

