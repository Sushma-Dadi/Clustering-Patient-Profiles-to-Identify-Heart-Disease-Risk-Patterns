# 🧠 Clustering Patient Profiles to Identify Heart Disease Risk Patterns

This project uses **unsupervised machine learning** techniques to segment patients based on cardiovascular risk indicators, aiming to support early detection and personalized healthcare strategies.

## 📊 Dataset

- **Source**: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/hosammhmdali/heart-disease-dataset)
- **Features**: Age, Cholesterol, Blood Pressure, ECG results, Exercise-induced angina, and more
- **Rows**: 1,048 records  
- **Target**: No labeled target — unsupervised clustering based on risk factors

## 🔍 Problem Statement

Traditional diagnostic approaches often miss subtle relationships between risk factors. This project explores whether **unsupervised learning** (clustering) can detect hidden patterns that identify patient risk levels for heart disease.

## ⚙️ Techniques Used

- Data Preprocessing: Encoding, Normalization (Z-score)
- **EDA**: Correlation analysis, statistical summaries
- **Dimensionality Reduction**: PCA (Principal Component Analysis)
- **Clustering Algorithms**:
  - K-Means Clustering
  - DBSCAN (Density-Based)
  - Hierarchical Clustering (Agglomerative)
- **Evaluation Metrics**: Silhouette Score, Davies-Bouldin Index
- **Visualization**: PCA plots, Heatmaps, Dendrograms

## 📈 Key Results

- K-Means performed best for cluster separation and interpretability
- DBSCAN identified outliers (extreme-risk patients)
- Hierarchical clustering showed relationships between risk levels
- Four distinct patient risk groups were identified based on features like **cholesterol**, **oldpeak**, and **exercise-induced angina**

## 🧪 How to Run

1. Download the `.ipynb` file from this repo
2. Open with **Jupyter Notebook**, **VS Code**, or **Google Colab**
3. Run the cells in order to reproduce data preprocessing, clustering, and visualizations

## 💡 Future Work

- Include more features: lifestyle, family history, medications
- Apply t-SNE/UMAP for deeper visual insights
- Validate clusters with clinical experts

## 👩‍💻 Author

**Sushma Dadi**  
Graduate Student, MS in Information Technology  
[LinkedIn](https://www.linkedin.com/in/sushmareddy-d)

