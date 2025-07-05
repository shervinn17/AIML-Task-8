# 🛍️ Mall Customer Segmentation using K-Means Clustering

This project performs **unsupervised learning** using **K-Means clustering** to segment customers based on their behavior. The dataset is visualized in 2D using PCA, and clustering quality is evaluated using the Elbow Method and Silhouette Score.

---

## 📌 Objective

- Segment mall customers into distinct groups based on spending habits and income.
- Use clustering for potential marketing strategies or business analysis.

---

## 🛠️ Tools & Libraries

- **Python**
- **Scikit-learn**
- **Pandas**
- **Matplotlib**
- **NumPy**

---

## 📁 Dataset

- **File**: `Mall_Customers.csv`
- **Columns Used**: 
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

---

## 🔧 Steps Performed

1. **Load & clean** the dataset (drop `CustomerID`, `Gender`).
2. **Standardize** the features using `StandardScaler`.
3. **Reduce dimensions** using PCA for 2D visualization.
4. **Find optimal K** using the **Elbow Method** (plot of inertia).
5. **Fit K-Means** with optimal K (e.g., K=5).
6. **Assign cluster labels** to each customer.
7. **Visualize clusters** in a 2D PCA plot with color-coded labels.
8. **Evaluate** clustering using **Silhouette Score**.

---

## 📊 Outputs

- 📈 **Elbow Plot** for selecting the optimal number of clusters.
- 🌀 **PCA Scatter Plot** showing distinct customer segments.
- 🧮 **Silhouette Score** indicating clustering effectiveness.

---

## 🚀 How to Run

1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
