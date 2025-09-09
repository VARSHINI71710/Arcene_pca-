# PCA + KMeans Clustering on Arcene Dataset

## 📌 Project Overview
This project demonstrates **Dimensionality Reduction (PCA)** and **Clustering (KMeans)** on the **Arcene dataset** from the UCI Repository.  
The dataset contains **10,000 features** per sample, making it a high-dimensional dataset. To handle this, **PCA** is applied to reduce dimensionality before clustering.

---

## 🚀 Steps Performed

### 1. Data Loading
- Loaded the dataset .
- Shape: `(n_samples, 10000 features)`.

### 2. Standardization
- Features were standardized using **StandardScaler** to ensure all features have mean = 0 and variance = 1.

### 3. Principal Component Analysis (PCA)
- Applied PCA to reduce dimensionality.
- Selected **5 components** (capturing most variance while keeping the dataset manageable).
- Checked:
  - **Explained variance ratio** for each component.
  - **Cumulative variance explained**.

### 4. KMeans Clustering
- Performed **KMeans clustering** on the reduced PCA features.
- Chosen number of clusters = **4**.
- Assigned each data point to a cluster.

### 5. Visualization
- Visualized the clusters using the **first 2 PCA components** in a scatter plot.
- Different colors represent different clusters.
