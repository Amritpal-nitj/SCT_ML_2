# SCT_ML_2
TASK2:Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

# 🧠 Customer Segmentation with K-Means

This project applies unsupervised machine learning to segment mall customers based on their **spending behavior** and **annual income**, helping businesses better understand and target their audience.

---

## 📊 Overview

We used **K-Means Clustering** on mall customer data to divide shoppers into distinct groups with similar purchasing habits. This can help retailers:
- Identify high-value customers
- Personalize marketing strategies
- Improve customer retention

---

## 📁 Dataset

- **File:** `Mall_Customers.csv`
- **Features Used:**
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🔧 Tools & Libraries

- Python
- Pandas & NumPy
- scikit-learn
- Matplotlib

---

## 🧪 Methodology

1. **Data Preparation**
2. **Feature Scaling** using `StandardScaler`
3. **Elbow Method** to determine optimal clusters
4. **K-Means Clustering**
5. **Visualization** of clusters and centroids
6. **Cluster Profiling**



## 💡 Cluster Insights

| Cluster | Description                          | Avg Income | Avg Spend | Size |
|---------|--------------------------------------|------------|-----------|------|
| 0       | Average earners & spenders           | ~$55k      | ~50       | 81   |
| 1       | High earners but conservative spenders | ~$88k   | ~17       | 35   |
| 2       | Low income, low spend                | ~$26k      | ~21       | 23   |
| 3       | Low income, high spend               | ~$26k      | ~79       | 22   |
| 4       | High income, high spend              | ~$87k      | ~82       | 39   |



## 📈 Visualizations

- Elbow Method plot to find optimal `k`
- 2D Cluster scatter plot with centroids


