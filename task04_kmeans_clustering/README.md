# Task-04: K-Means Clustering  
### Prodigy InfoTech – Data Science Internship

This project performs **Customer Segmentation** using the **K-Means Clustering Algorithm** on the Mall Customers dataset.  
The goal is to identify customer groups based on:

- Annual Income  
- Spending Score  

---

## 📊 Dataset Description

| Column Name               | Description |
|---------------------------|-------------|
| CustomerID                | Unique ID for each customer |
| Gender                    | Male / Female |
| Age                       | Customer age |
| Annual Income (k$)        | Income level |
| Spending Score (1-100)    | Score assigned based on spending behavior |

---

## 🧠 Steps Performed

### 1. **Data Loading**
Loaded `mall_customers.csv` and explored structure & statistics.

### 2. **Preprocessing**
- Converted Gender into numeric values (Male = 0, Female = 1)
- Selected features for clustering

### 3. **Elbow Method**
Used inertia values for `k = 1 to 10` to identify the optimal number of clusters.

### 4. **K-Means Clustering**
Performed clustering using:
- Annual Income
- Spending Score

Added cluster labels to the dataset.

### 5. **Visualization**
Plotted:
- Customer Segmentation scatterplot
- Cluster centroids

---

## 📈 Interpretation of Clusters

Typical output:

- **Cluster 0** → Low Income, Moderate Spending  
- **Cluster 1** → High Income, High Spending (Premium Customers)  
- **Cluster 2** → Low Income, Low Spending  
- **Cluster 3** → High Income, Low Spending  

---

## 🚀 Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📌 Internship Deliverable

This fulfills the **K-Means Clustering** requirement of the Prodigy InfoTech Data Science Internship.

---

## ✨ Author

**Sanjay Karthi**  
GitHub: https://github.com/sanjaykarthirp
