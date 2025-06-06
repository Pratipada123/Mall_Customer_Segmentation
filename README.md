# Mall_Customer_Segmentation

# Task 8: K-Means Clustering and Evaluation

This project demonstrates the use of K-Means clustering on a dataset using various steps such as data visualization, dimensionality reduction (PCA), elbow method for optimal cluster selection, and evaluation using Silhouette Score.

## 📌 Key Steps

1. **Load and Prepare Dataset**  
   Load a dataset (e.g., from `sklearn.datasets`) and standardize features for clustering.

2. **Visualize with PCA (Optional)**  
   Apply Principal Component Analysis (PCA) to reduce features to 2D for visualization.

3. **Apply K-Means Clustering**  
   Fit K-Means with a selected number of clusters and assign labels to data points.

4. **Elbow Method**  
   Determine the optimal number of clusters by plotting the within-cluster sum of squares (WCSS) against the number of clusters.

5. **Cluster Visualization**  
   Visualize clusters in 2D with color-coding using PCA components.

6. **Evaluation with Silhouette Score**  
   Evaluate clustering quality using the silhouette score.

## 📊 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn (KMeans, PCA, Silhouette Score)

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
