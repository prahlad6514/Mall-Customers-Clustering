# Customer Segmentation (Mall Customers)

This project demonstrates customer segmentation using the Mall Customers dataset and K-Means clustering.

## 📖 Project Overview
Customer segmentation helps businesses understand different groups of customers based on their behavior and demographics.  
Here, we use the Mall Customers dataset to apply **K-Means clustering** and identify distinct customer groups.

## 📊 Dataset Details
- **CustomerID**: Unique ID  
- **Gender**: Male/Female  
- **Age**: Customer age  
- **Annual Income (k$)**: Income in thousands  
- **Spending Score (1–100)**: Score assigned based on spending behavior  

## 🛠️ Tools & Libraries
- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

## 🚀 Workflow
1. Load dataset (`Mall_Customers.csv`)  
2. Perform Exploratory Data Analysis (EDA)  
3. Visualize distributions (Age, Income, Spending Score)  
4. Apply **K-Means clustering**  
5. Visualize clusters (Annual Income vs Spending Score)  
6. Interpret customer segments  

## 📷 Results
Example cluster visualization (Annual Income vs Spending Score):  
![Cluster Visualization](clusters.png)

## ⚙️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook Customer_Segmentation.ipynb
