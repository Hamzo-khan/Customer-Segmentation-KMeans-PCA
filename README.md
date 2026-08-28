# Customer Segmentation using K-Means & PCA

## 📌 Project Overview

This project focuses on customer segmentation using Machine Learning.

The main goal is to divide customers into different groups based on their:

- Age
- Annual Income
- Spending Score

K-Means Clustering was used to identify customer segments, while PCA (Principal Component Analysis) was used to visualize the clusters in two dimensions.

---

## 🎯 Project Objective

The objective of this project is to:

- Understand customer behavior
- Identify different customer segments
- Find groups of similar customers
- Help businesses create targeted marketing strategies
- Improve customer engagement and decision-making

---

## 📂 Dataset

The dataset contains customer information including:

- Age
- Annual Income (k$)
- Spending Score (1-100)

After data cleaning, the final dataset contained **982 customers**.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 🔎 Project Workflow

The project followed these steps:

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Outlier Detection
6. Feature Scaling
7. Elbow Method
8. K-Means Clustering
9. PCA Visualization
10. Cluster Profiling
11. Cluster Size Analysis
12. Silhouette Score
13. Business Insights and Recommendations

---

## 📊 Exploratory Data Analysis

EDA was performed to understand the distribution and relationships between customer features.

The analysis included:

- Age distribution
- Annual income distribution
- Spending score distribution
- Relationships between customer features
- Outlier analysis

---

## ⚙️ Feature Scaling

StandardScaler was used to standardize the selected features:

- Age
- Annual Income
- Spending Score

This was important because the features have different scales.

---

## 📈 Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

The analysis indicated that:

**Optimal K = 4**

Therefore, four customer segments were created using K-Means Clustering.

---

## 🤖 K-Means Clustering

K-Means Clustering was applied with:

**Number of Clusters = 4**

The algorithm grouped customers based on similarities in their age, income, and spending behavior.

---

## 🔬 PCA Visualization

Principal Component Analysis (PCA) was used to reduce the three selected features into two principal components for visualization.

### Explained Variance

- PC1: **91.32%**
- PC2: **6.17%**
- Total: **97.49%**

Together, the two principal components preserve **97.49% of the total variance**.

---

## 👥 Customer Segments

The four customer segments were identified as:

| Cluster | Customer Segment |
|--------|-------------------|
| 0 | Average Customers |
| 1 | High-Income, Very Low-Spending Customers |
| 2 | Higher-Income, Low-Spending Customers |
| 3 | Young, High-Spending Customers |

---

## 📊 Cluster Profiles

### Cluster 0 — Average Customers

- Average Age: **35.52**
- Average Income: **49.47k**
- Average Spending Score: **47.89**

These customers have moderate income and moderate spending behavior.

### Cluster 1 — High-Income, Very Low-Spending Customers

- Average Age: **66.70**
- Average Income: **107.58k**
- Average Spending Score: **4.98**

These customers have high income but very low spending behavior.

### Cluster 2 — Higher-Income, Low-Spending Customers

- Average Age: **45.05**
- Average Income: **81.27k**
- Average Spending Score: **30.24**

These customers have relatively high income but lower spending behavior.

### Cluster 3 — Young, High-Spending Customers

- Average Age: **27.33**
- Average Income: **29.48k**
- Average Spending Score: **60.42**

These customers are younger and have relatively low income but show high spending behavior.

---

## 📏 Model Evaluation

The clustering model was evaluated using the Silhouette Score.

**Silhouette Score: 0.381**

This indicates a moderate level of separation between the customer clusters, with some overlap between groups.

---

## 💡 Business Insights

Different customer segments require different marketing strategies.

### Cluster 0
Use loyalty programs, regular promotions, and bundle offers.

### Cluster 1
Use personalized marketing, premium offers, and special incentives to increase spending.

### Cluster 2
Use targeted discounts, product recommendations, and promotional campaigns.

### Cluster 3
Use trendy products, social media marketing, limited-time offers, and loyalty rewards.

---

## 📌 Business Value

Customer segmentation can help businesses:

- Understand customer behavior
- Create targeted marketing campaigns
- Improve customer engagement
- Identify high-value customer groups
- Increase customer spending
- Improve marketing efficiency
- Make data-driven business decisions

---

## 🚀 Conclusion

The K-Means algorithm successfully divided the customers into four meaningful segments based on age, annual income, and spending score.

PCA provided an effective two-dimensional visualization while preserving **97.49% of the total variance**.

The identified customer segments can help businesses develop personalized marketing strategies and make better customer-focused decisions.

---

## 👨‍💻 Author

**Hamza-khan**

### Project

**Customer Segmentation using K-Means & PCA**
