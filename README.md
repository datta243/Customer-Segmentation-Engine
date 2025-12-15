# 📊 Customer Segmentation Engine  
### (Python · Machine Learning · Data Visualization)

---

## 🔍 Project Overview

Customer behavior varies significantly across individuals, and treating all customers the same leads to inefficient marketing and poor retention.  
This project builds an **end-to-end Customer Segmentation Engine** that groups customers based on purchasing behavior using **RFM analysis** and **K-Means clustering**, and validates insights through **Python-based data visualizations**.

The system helps answer key business questions:
- Who are the most valuable customers?
- Which customers are at risk of churn?
- How does customer behavior differ across segments?

---

## 📁 Project Structure

│
├── data/

│ ├── online_retail_II.xlsx(https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset?resource=download)

│

├── notebooks/

│ ├── 01_data_cleaning.ipynb

│ ├── 02_rfm_analysis.ipynb

│ └── 03_clustering_segmentation.ipynb

│

├── visualizations/

│ └── customer_segmentation_plots.ipynb

│

└── README.md
---

## 🛠️ Tech Stack

### Data Processing & Machine Learning
- Python
- Pandas, NumPy
- Scikit-learn

### Visualization
- Matplotlib
- Seaborn

---

## 🧠 Methodology

### 1️⃣ Data Cleaning
- Removed missing customer IDs
- Filtered cancelled transactions
- Removed zero or negative quantity and price values
- Created transaction-level total revenue

### 2️⃣ Feature Engineering (RFM Analysis)
- **Recency:** Days since the customer’s last purchase
- **Frequency:** Number of distinct purchases
- **Monetary:** Total revenue generated per customer

### 3️⃣ Feature Scaling
- Standardized RFM features using `StandardScaler` to ensure fair clustering

### 4️⃣ Customer Segmentation
- Applied **K-Means clustering**
- Determined optimal number of clusters using the **Elbow Method**
- Segmented customers into **four distinct behavioral groups**

### 5️⃣ Visualization & Insight Validation
- Used Python visualizations to analyze:
  - Customer distribution by segment
  - Revenue contribution per segment
  - RFM behavior across segments
  - Churn risk using recency analysis

---

## 📈 Key Visualizations (Python)

The following plots were created using **Matplotlib and Seaborn**:
- Customer distribution by segment (bar chart)
- Revenue contribution by segment
- Average RFM values per segment
- Frequency vs Monetary scatter plot
- Average recency per segment (churn indicator)
- Monetary distribution using box plots

These visualizations were used to **validate clustering quality** and **derive business insights**.

---


