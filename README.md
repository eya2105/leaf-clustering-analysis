# 🍃 Leaf Clustering using Unsupervised Learning

This project focuses on the unsupervised classification (clustering) of leaf images using various machine learning techniques. We aim to group similar leaf types based on image descriptors and evaluate clustering performance both qualitatively and quantitatively.

---

## Dataset

We use a dataset of 1584 leaf images named from `1.jpg` to `1584.jpg`. Each image is associated with pre-computed descriptors (e.g., margin, shape, texture) and class labels for evaluation purposes.

---

## Objectives

- Apply dimensionality reduction techniques (like PCA) to visualize and preprocess high-dimensional descriptors.
- Perform unsupervised clustering (KMeans, CAH).
- Evaluate clustering quality using:
  - Adjusted Rand Index (ARI)
  - Silhouette Score
- Visually inspect clusters by displaying representative images.

---

## Technologies Used

- Python 3.9
- Jupyter Notebook 
- `pandas`, `numpy`
- `matplotlib`
- `scikit-learn`
- `os`, `matplotlib.image`

---

## Methods

### Preprocessing
- Normalization of descriptors
- PCA for dimensionality reduction (keeping 95% variance)

### Clustering
- KMeans clustering
- Agglomerative Hierarchical Clustering (CAH)
- Elbow Method and Silhouette Score to choose optimal cluster count

### Evaluation
- Adjusted Rand Index (quantitative)
- Cluster visualization (qualitative)

---

##  Key Results

- PCA reduced the descriptors to **69 components**, preserving 95% of variance.
- Clustering with KMeans yielded:
  - **ARI** ≈ 0.33
  - **Silhouette Score** ≈ 0.18
- Visual inspection of clustered images showed moderate coherence between visual similarity and assigned clusters.

---




