# 🛍️ K-Means Customer Segmentation  
**SkillCraft Technology – Machine Learning Internship (Task: SCT_ML_2)**  

📌 **Customer Segmentation Project using K-Means Clustering**  
A complete machine learning pipeline built as part of the SkillCraft Technology ML Internship, focusing on grouping customers based on income and spending behavior to enable data-driven marketing strategies.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)  
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)](https://scikit-learn.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🎯 Project Overview

This project identifies distinct customer groups using **K-Means clustering**, enabling businesses to:

- Personalize marketing campaigns  
- Improve customer targeting  
- Optimize product recommendations  
- Increase customer retention  

The dataset contains customer demographic and behavioral features such as **Gender, Age, Annual Income**, and **Spending Score**.

---

## 📁 Dataset Information

- **Dataset:** Mall Customer Segmentation  
- **Source:** Kaggle  
- **Rows:** 200  
- **Features:** 5  
- **Learning Type:** Unsupervised Machine Learning  
- **Goal:** Identify distinct customer profiles  

---

## 📊 Key Features of the Project

✔ Full Exploratory Data Analysis (EDA)  
✔ Data Cleaning & Preprocessing  
✔ Standard Scaling using StandardScaler  
✔ K-Means with K-Means++ initialization  
✔ Optimal K selection using Elbow Method & Silhouette Score  
✔ Cluster Visualization  
✔ Spending & Gender Behavior Insights  
✔ Performance Metrics Visualization  
✔ Executive Dashboard  
✔ Exported CSV Reports  

---

## 📸 Visualizations

### ⭐ 1. Exploratory Data Analysis  
`comprehensive_eda.png`

### ⭐ 2. Optimal K Selection (Elbow + Silhouette)  
`optimal_k_analysis.png`

### ⭐ 3. Final Cluster Map  
`cluster_analysis.png`

### ⭐ 4. Model Performance Metrics  
`performance_metrics.png`

### ⭐ 5. Executive Dashboard  
`executive_dashboard.png`

---

## 📂 Project Structure

```
SCT_ML_2/
├── SCT_ML_2_Customer_Segmentation.ipynb     # Main notebook
├── customer_segments_results.csv            # Cluster labels
├── cluster_summary.csv                      # Summary statistics
├── cluster_centroids.csv                    # Cluster center values
├── comprehensive_eda.png                    # EDA visualizations
├── optimal_k_analysis.png                   # Elbow + Silhouette plot
├── cluster_analysis.png                     # Final cluster visualization
├── performance_metrics.png                  # Metrics bar chart
├── executive_dashboard.png                  # Final dashboard
└── README.md                                # Documentation
```

---

## 🛠️ Technologies Used

- Python 3.8+  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Google Colab / Jupyter Notebook  

---

## 📈 Model Performance

> Replace these placeholders with your actual printed metric scores.

| Metric                      | Score  |
| --------------------------- | ------ |
| **Silhouette Score**        | 0.XXX  |
| **Davies–Bouldin Score**    | X.XXX  |
| **Calinski–Harabasz Index** | XXXX.X |

**Interpretation:**  
- Silhouette → Higher is better  
- Davies–Bouldin → Lower is better  
- Calinski–Harabasz → Higher is better  

---

## 👥 Identified Customer Segments

| Cluster | Segment Name | Description | Recommended Strategy |
|--------|--------------|-------------|----------------------|
| C1 | High-Value Customers | High income, high spending | Premium services, VIP offers |
| C2 | Potential Customers | High income, low spending | Targeted promotions |
| C3 | Standard Customers | Mid income, mid spending | Loyalty programs |
| C4 | Budget Customers | Low income, low spending | Affordable bundles |
| C5 | Low-Engagement Customers | Low interaction | Awareness campaigns |

---

## 🚀 How to Run

### ▶ Run in Google Colab  
Upload the notebook and run all cells.

### ▶ Run Locally  
```bash
pip install -r requirements.txt
jupyter notebook SCT_ML_2_Customer_Segmentation.ipynb
```

---

## 🎓 Skills Gained

- Unsupervised learning  
- K-Means clustering  
- Data preprocessing & scaling  
- Cluster evaluation metrics  
- Dashboard development  
- Business analytics from data  

---

## 👨‍💻 Author

### **Rahul R**  
Machine Learning Intern – SkillCraft Technology  
📧 **rahulheamanth2004@gmail.com**  
🔗 LinkedIn: **https://www.linkedin.com/in/rahul-r2004**

---


## 🙏 Acknowledgments

- Dataset from Kaggle  
- SkillCraft Technology for the internship guidance  

---

⭐ **If this project helped you, please star the repository!** ⭐
