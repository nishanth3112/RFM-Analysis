# Customer Segmentation using RFM Analysis 🛍️📊

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Data-Pandas-yellow)
![NumPy](https://img.shields.io/badge/Library-NumPy-lightblue)
![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-green)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-red)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-orange)
![Jupyter](https://img.shields.io/badge/IDE-Jupyter%20Notebook-purple)
![Clustering](https://img.shields.io/badge/Model-KMeans-brown)

📅 Date: Oct 2024
👤 Authors: Nishanth Manoharan, Parth Saraykar, Rishik Ganta  
🛠️ Tech Stack: Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn), Jupyter Notebook  

---

## 📌 Overview
This project applies **RFM Analysis (Recency, Frequency, Monetary)** to an **eCommerce dataset** from [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data).  

The goal is to **segment customers** based on purchasing behavior and provide **actionable insights for marketing, retention, and revenue growth**.  

✅ **Impact**: Identified high-value customers, dormant customers, and spending patterns; delivered targeted marketing strategies to optimize engagement:contentReference[oaicite:0]{index=0}.  

---

## 🚀 Workflow & Methodology
1. **Data Preprocessing** 🧹  
   - Cleaned dataset of ~540K rows & 8 columns.  
   - Handled missing values, converted dates, standardized column names, removed duplicates:contentReference[oaicite:1]{index=1}.  

2. **RFM Calculation** 📊  
   - **Recency** = Days since last purchase.  
   - **Frequency** = Number of purchases.  
   - **Monetary** = Total spend.  
   - Generated RFM scores for each of 4,372 unique customers:contentReference[oaicite:2]{index=2}.  

3. **RFM Segmentation** 🏷️  
   - Assigned quartile-based scores (1–4).  
   - Built composite RFM codes (e.g., 432).  

4. **Customer Clustering (K-Means)** 🤖  
   - Standardized RFM scores.  
   - Determined **k=3** using the **Elbow Method**.  
   - Segmented customers into 3 behavioral clusters:contentReference[oaicite:3]{index=3}.  

5. **Segment Profiling** 👥  
   - **Cluster 1:** Recent but infrequent high spenders.  
   - **Cluster 2:** “Champions” – high frequency, high value customers.  
   - **Cluster 3:** Dormant/low-value customers requiring re-engagement:contentReference[oaicite:4]{index=4}.  

6. **Visualization** 📉  
   - Bar charts of average RFM scores.  
   - Scatter plots (R vs F, F vs M, R vs M).  
   - Heatmap of RFM correlations.   

7. **Marketing Recommendations** 💡  
   - Loyalty programs for **Champions**.  
   - Re-engagement offers for **Dormant** customers.  
   - Upselling for **Recent but Infrequent** buyers.  
   - Premium bundles for **High Spenders**.  
   - Educational campaigns for **Low-Value** customers:contentReference[oaicite:6]{index=6}.  

---

## 📊 Key Features
✅ **RFM Analysis** – Data-driven segmentation using Recency, Frequency, Monetary metrics.  
✅ **K-Means Clustering** – Grouped customers into 3 actionable clusters.  
✅ **Behavioral Insights** – Identified Champions, Dormant users, High Spenders, etc.  
✅ **Marketing Recommendations** – Practical strategies to improve engagement & retention.  
✅ **Visual Analytics** – Scatter plots, heatmaps, and bar charts for customer behavior:contentReference[oaicite:7]{index=7}.  

---

## ⭐ Contribute & Connect
💡 If you find this repo useful, star ⭐ this repo!  

🔗 LinkedIn: [Nishanth Manoharan](https://www.linkedin.com/in/nishanth-manoharan-/)  
🔗 GitHub: [nishanth3112](https://github.com/nishanth3112)  
