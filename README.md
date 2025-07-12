# 🛍️ Customer Segmentation using K-Means Clustering

This project uses the **K-Means clustering algorithm** to segment customers of a retail store based on their **Annual Income** and **Spending Score**. The goal is to help businesses understand customer behavior and group them into distinct market segments for better decision-making.

---

## 📌 Objective

- Group customers into clusters based on purchasing behavior
- Visualize and interpret clusters to improve marketing strategies
- Identify optimal number of customer groups using the Elbow Method and Silhouette Score

---

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- scikit-learn (KMeans, StandardScaler, silhouette_score)
- Seaborn, Matplotlib

---

## 📁 Dataset

- **File:** `Mall_Customers.csv`
- **Source:** Mall customer data (contains Customer ID, Gender, Age, Annual Income, Spending Score)
- **Features Used:**  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`

---

## ⚙️ How to Run

```bash
# Step 1: Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn

# Step 2: Run the script
python customer_segmentation.py
