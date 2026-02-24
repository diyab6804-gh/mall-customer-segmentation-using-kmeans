# 🛍️ Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means Clustering**, an unsupervised machine learning technique, to segment mall customers based on their **annual income and spending behavior**. The goal is to identify distinct customer groups that can help businesses develop **targeted marketing strategies and personalized services**.

---

## 🎯 Objectives
- Perform unsupervised learning using K-Means
- Determine optimal number of clusters using Elbow Method
- Visualize clusters with color coding
- Apply PCA for 2D visualization
- Evaluate clustering using Silhouette Score

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📊 Dataset
**Mall Customer Segmentation Dataset (Kaggle)**

**Features:**
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)  

---

## ⚙️ Project Workflow
1. Data Loading & Exploration  
2. Feature Selection & Scaling  
3. Elbow Method for Optimal K  
4. K-Means Model Training  
5. Cluster Visualization  
6. PCA for 2D Visualization  
7. Silhouette Score Evaluation  

---

## 📈 Elbow Method
The Elbow Method is used to determine the optimal number of clusters by plotting **WCSS vs K**.  
The optimal number of clusters was found to be **K = 5**.

---

## 🎨 Cluster Visualization
Clusters are visualized using scatter plots and color coding.  
PCA is applied to reduce dimensionality for better **2D decision boundary visualization**.

---

## 🧠 Business Insights
- High Income – High Spending → Premium Customers  
- High Income – Low Spending → Careful Customers  
- Low Income – High Spending → Target Customers  
- Low Income – Low Spending → Budget Customers  
- Medium Income – Medium Spending → Regular Customers  

---

## 🏆 Results
- Optimal clusters identified successfully  
- High Silhouette Score indicating strong cluster separation  
- Clear customer segmentation enabling business intelligence  

---

## 📁 Repository Structure

```
mall-customer-segmentation-using-kmeans/
│
├── data/
│   └── Mall Customers dataset.csv
│
├── notebooks/
│   └── Task8_Mall_Customer_Segmentation_Using_KMeans.ipynb
│
├── reports/
│   └── Task8_mall_customer_segmentation_using_kmeans.pdf
│
├── README.md

```

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/diyab6804-gh/mall-customer-segmentation-using-kmeans.git
   
2. Install dependencies
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Jupyter Notebook
   ```
   jupyter notebook

---

## 🏁 Conclusion

This project successfully demonstrates the application of K-Means clustering for customer segmentation. The results provide valuable insights that can significantly help businesses improve marketing strategies and customer experience.

---

## 👩‍💻 Author

Patel Diya B

AI/ML Intern
