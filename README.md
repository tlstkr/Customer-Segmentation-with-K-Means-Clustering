# Customer Segmentation using K-Means Clustering

## 📌 Overview

In this repository, I implemented a **customer segmentation model** using **K-Means clustering**. Customer segmentation helps businesses group customers based on their purchasing behaviors, enabling **personalized marketing strategies** and **targeted services**. By leveraging clustering techniques, we can move beyond one-size-fits-all marketing approaches and optimize customer engagement.

---

## 📂 Dataset

For this project, I used the **Online Retail dataset** from the **UCI Machine Learning Repository**. This dataset contains the purchase history of a UK-based online retail store, including:

- 🧾 **Invoice Number**
- 🔢 **Stock Code**
- 🏷 **Product Description**
- 📦 **Quantity Purchased**
- 🗓 **Invoice Date**
- 💰 **Unit Price**
- 👤 **Customer ID**
- 🌍 **Country of Purchase**

---

## 🚀 Approach

### 🔹 1. Data Preprocessing  
✅ Handled missing values and removed anomalies.  
✅ Processed purchase data to extract meaningful customer insights.  
✅ Standardized numerical data for clustering.  

### 🔹 2. Feature Engineering  
✅ Created **RFM (Recency, Frequency, Monetary)** features to quantify customer behavior.  

### 🔹 3. Clustering with K-Means  
✅ Applied **K-Means clustering** to segment customers based on RFM values.  
✅ Determined the optimal number of clusters using the **Elbow Method**.  

### 🔹 4. Visualization & Insights  
✅ Used **Plotly** to visualize clusters and analyze customer behavior.  
✅ Interpreted segment characteristics to derive actionable business insights.  

---

## 📊 Results & Business Implications

Through this analysis, I identified **distinct customer segments** based on their purchasing behavior. These insights can be used by businesses to:

📌 **Personalize marketing strategies** for different customer groups.  
📌 **Optimize inventory and pricing** based on high-value customer behavior.  
📌 **Improve customer retention** through targeted promotions.  

### 📉 Cluster Visualization:

#### 📌 Customer Segments Identified by K-Means:
![newplot](https://github.com/user-attachments/assets/828d319c-765e-4282-9c00-48e32c5abe8c)


This visualization shows the different customer groups based on RFM analysis, helping businesses understand the distinct behaviors of their customer base.

---

## 🛠 Tools & Libraries Used

📌 **Python (Jupyter Notebook)**  
📌 **Pandas** – for data manipulation  
📌 **Scikit-learn** – for clustering and preprocessing  
📌 **Plotly** – for interactive visualizations  

---

## 📩 Contact

If you have any questions or feedback, feel free to reach out! 🚀  
📧 Email: tlstkr@gmail.com
---

### ⭐ If you found this project useful, consider giving it a star! ⭐
