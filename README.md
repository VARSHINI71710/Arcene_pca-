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

Clustered plot in graph:

<img width="679" height="547" alt="image" src="https://github.com/user-attachments/assets/38d89541-1337-495b-9012-50a13f36d6ae" />

Scree plot:

<img width="708" height="470" alt="image" src="https://github.com/user-attachments/assets/456e0ad7-6d88-468e-94b1-27be79fcdbde" />

