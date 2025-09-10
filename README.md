# EcommerceSegmenatation
Customer segmentation analysis on an e-commerce dataset using RFM (Recency, Frequency, Monetary) analysis and KMeans clustering. This project identifies high-value customers and visualizes customer segments with interactive plots.

## 📌 Objective

E-commerce businesses need to understand customer behavior to improve retention and sales. This notebook:

- Segments customers based on purchasing behavior  
- Identifies high-value and loyal customers  
- Visualizes customer clusters for easy interpretation  

---

## 🛠 Notebook Features

- **Data Cleaning & Preprocessing**  
  - Handles missing values and cancelled orders  
  - Computes total transaction value per order  

- **RFM Feature Engineering**  
  - Recency: Days since last purchase  
  - Frequency: Total number of purchases  
  - Monetary: Total spending  

- **KMeans Clustering**  
  - Groups customers into meaningful segments  
  - Cluster labels for business interpretation  

- **Visualizations**  
  - Cluster distribution  
  - RFM pairplots  
  - Recency vs Monetary scatter plots  

- **Top Customers Analysis**  
  - Identifies top high-value customers for targeted campaigns  

---

## 💻 How to Run

1. Open this notebook on Kaggle.  
2. Run all cells.  
3. All plots and tables will be displayed inline.  
4. Clustered customer data is saved in the output folder.

---

## 📂 Notebook Structure

- **Data Loading & Cleaning**  
- **RFM Feature Engineering**  
- **KMeans Clustering**  
- **Cluster Labeling & Interpretation**  
- **Visualization & Insights**  
- **Top Customer Extraction**

---

## 🧩 Cluster Segments
--------------------------------------------------------------
| Cluster Label       | Description                          |
|---------------------|--------------------------------------|
| High-Value          | High spending and frequent customers | 
| Frequent-Low-Value  | Loyal customers with moderate spend  |
| Low-Value           | Inactive or low-value customers      |
| Lost                | Customers not active recently        |
--------------------------------------------------------------
---

## ⚡ Technologies Used

- **Python**  
- **Pandas & NumPy**  
- **Scikit-learn (KMeans, StandardScaler)**  
- **Matplotlib & Seaborn**  

---

## 🔗 References


- Python, Pandas, Scikit-learn documentation  

---

This notebook is fully **Kaggle-ready** with **interactive visualizations** and **insights**, suitable for portfolios or competitions.
