# 🌼 Iris Dataset Clustering - Unsupervised Learning Project

This project applies **KMeans** and **Hierarchical Clustering** techniques to the famous **Iris dataset** using unsupervised learning methods.

---

## 📊 Dataset

- **Source**: `sklearn.datasets.load_iris`
- **Features**: 4 numeric features (sepal/petal length & width)
- **Target**: Not used (unsupervised learning)

---

## 🧪 Objective

1. Apply clustering techniques to discover natural groupings in the data.
2. Visualize clusters using KMeans and Hierarchical clustering.
3. Understand the structure of the Iris dataset without using labels.

---

## 📦 Methods

### 🔹 KMeans Clustering
- Clusters data into `k` groups based on nearest centroids.
- Efficient and simple to implement.
- Suitable for datasets with clear spherical clusters.

### 🔹 Hierarchical Clustering
- Builds a tree (dendrogram) of nested clusters.
- Doesn’t require pre-defined `k`.
- Useful for exploratory data analysis.

---

## 📈 Results

- **Both KMeans and Hierarchical clustering** revealed natural clusters similar to actual species in the dataset.
- **Visualizations** using the first two principal features provided good separation among clusters.

---

## 📁 Project Structure

```
.
├── iris_clustering.ipynb       # Main Jupyter Notebook
├── README.md                   # Project Documentation
```

---

## 🚀 How to Run

1. Clone this repository
2. Install dependencies (`scikit-learn`, `matplotlib`, `seaborn`, `scipy`)
3. Run the notebook step-by-step

---

## 📝 Author & License

- Developed for a machine learning clustering assessment.
- Licensed under the [MIT License](LICENSE) *(if applicable)*
