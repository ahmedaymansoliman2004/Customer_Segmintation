<img width="1024" height="819" alt="Logo" src="https://github.com/user-attachments/assets/e64a2c69-f713-471b-9ea4-b088d1ab3389" />

# 🛍 Customer Segmentation using K-Means & DBSCAN

## 📖 Project Overview

Customer segmentation is a key technique in data analysis that helps businesses divide customers into meaningful groups based on shared characteristics. 

In this project, we apply **unsupervised machine learning algorithms** to segment customers using the Mall Customers dataset. The segmentation is based on two main features:

- Annual Income (k$)
- Spending Score (1–100)

The goal is to identify distinct customer groups and interpret them from a business perspective.

---

## 📊 Dataset

- Dataset: Mall Customers (Kaggle)
- Total Records: 200 customers
- Features:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

For clustering, we used:
- Annual Income
- Spending Score

---

## ⚙️ Project Steps

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Feature Selection
4. Data Scaling using StandardScaler
5. Determine optimal clusters using Elbow Method
6. Apply K-Means Clustering
7. Visualize clusters using 2D scatter plot
8. Compare with DBSCAN algorithm
9. Business interpretation of clusters

---

## 🤖 Algorithms Used

### 🔹 K-Means
- Determined optimal number of clusters using Elbow Method
- Final number of clusters: **5**
- Produced well-separated and balanced customer segments

### 🔹 DBSCAN
- Density-based clustering algorithm
- Detected fewer clusters
- Identified some points as noise
- Less suitable for this dataset compared to K-Means

---

## 📈 Results

- K-Means successfully identified 5 distinct customer segments.
- Clusters represent different customer behaviors such as:
  - High-income high-spending (VIP customers)
  - High-income low-spending (growth opportunity)
  - Low-income high-spending (promotion-driven customers)
  - Low-income low-spending customers
  - Average customers

- Silhouette Score was used to compare clustering quality.
- K-Means outperformed DBSCAN for this dataset.

---

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 💡 Key Learnings

- Importance of feature scaling in distance-based algorithms
- How to determine optimal cluster count using Elbow Method
- Differences between centroid-based and density-based clustering
- How to translate clustering results into business insights

---

## 🚀 Future Improvements

- Add more behavioral features
- Apply PCA for dimensionality reduction
- Experiment with Hierarchical Clustering
- Deploy as an interactive dashboard

---

## 📌 Author

Ahmed Ayman Soliman

If you found this project helpful, feel free to ⭐ the repository.
