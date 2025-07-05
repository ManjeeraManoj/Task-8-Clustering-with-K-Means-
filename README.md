# Task 8 - K-Means Clustering on Mall Customers Dataset

## Objective
Perform unsupervised learning using K-Means clustering on a customer dataset to segment customers based on spending behavior.

---

## 📊 Dataset
- **File:** `Mall_Customers.csv`
- **Features Used:** Age, Annual Income (k$), Spending Score (1-100)

---

## 🛠 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 💡 Steps Performed

1. **Data Preprocessing**
   - Loaded dataset and removed unnecessary columns (`CustomerID`, `Gender`).
   - Standardized features using `StandardScaler`.

2. **Elbow Method**
   - Plotted inertia for K=1 to 10.
   - Found optimal K visually (K=5).

3. **Model Training**
   - Fitted KMeans with optimal K=5.
   - Predicted and assigned cluster labels.

4. **Visualization**
   - Plotted clusters using `Annual Income` vs `Spending Score`.

5. **Evaluation**
   - Calculated Silhouette Score for the clustering.

---

## 📈 Results
- **Optimal Clusters (K):** 5
- **Silhouette Score:** *Varies around ~0.45–0.60* depending on random state

---

## 📎 Files Included
- `kmeans_clustering.py` - Main script
- `Mall_Customers.csv` - Dataset
- `README.md` - Project explanation

---

## 📌 Notes
- PCA can be used optionally for 2D visualization.
- You can try varying the `random_state` or features for better results.
