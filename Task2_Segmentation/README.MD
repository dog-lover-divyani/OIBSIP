# Customer Segmentation Analysis (E-commerce)

## 📌 Project Overview
This project performs **customer segmentation analysis** for an e-commerce business using data analytics and clustering techniques.  
The objective is to group customers into meaningful segments based on their purchasing behavior, enabling **targeted marketing strategies**, improved customer engagement, and data-driven business decisions.

---

## 🎯 Project Objectives
- Analyze customer demographics and purchasing behavior
- Clean and preprocess raw customer data
- Apply clustering algorithms to segment customers
- Visualize customer groups and interpret patterns
- Generate actionable insights for business strategy

---

## 🗂 Dataset Description
The dataset contains customer-related information such as:
- Income
- Spending behavior across product categories
- Demographic attributes
- Purchase frequency and amount

The data was cleaned and prepared to ensure consistency and usability before analysis.

---

## 🛠 Tools & Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – clustering (K-Means)

---

## 🔍 Methodology

### 1️⃣ Data Cleaning & Exploration
- Checked for missing values and inconsistencies
- Standardized numerical features
- Performed descriptive statistical analysis

### 2️⃣ Feature Scaling
- Applied feature scaling to ensure equal contribution of variables in clustering

### 3️⃣ Clustering (K-Means)
- Used the **Elbow Method** to determine the optimal number of clusters
- Applied K-Means clustering to segment customers

---

## 📈 Visualizations

### 📉 Elbow Method for Optimal Clusters
The elbow curve helps identify the most suitable number of clusters by analyzing inertia values.

![Elbow Method]("C:\Users\divya\OneDrive\Desktop\projects\OIBSIP\Task2_Segmentation\elbow_method.png")

---

### 📊 Customer Segments: Income vs Total Spending
This scatter plot visualizes customer groups based on income and overall spending behavior.

![Customer Segments]("C:\Users\divya\OneDrive\Desktop\projects\OIBSIP\Task2_Segmentation\customer_segments_income_vs_spending.png")

---

## 📁 Exported Outputs
The final results were saved for further analysis and reporting:

- 📄 [Clustered Customers Dataset]("C:\Users\divya\OneDrive\Desktop\projects\OIBSIP\Task2_Segmentation\customer_segmentation_results.csv")


---

## 🧠 Key Insights
- Customers can be clearly grouped into **distinct behavioral segments**
- High-income customers do not always correspond to high spending
- Certain clusters represent high-value customers suitable for premium targeting
- Some segments indicate low engagement, highlighting retention opportunities

---

## 📌 Business Recommendations
- Target high-spending clusters with loyalty programs
- Use personalized marketing for medium-spending segments
- Design re-engagement strategies for low-spending customers
- Apply segmentation insights to optimize promotions and pricing strategies

---

## ✅ Conclusion
This project demonstrates how **customer segmentation using data analytics** can uncover hidden patterns in customer behavior.  
By leveraging clustering and visualization techniques, businesses can make informed decisions that enhance customer satisfaction and improve overall performance.

---

## 📎 Repository Structure
Task2_Segmentation/
│
├── customer_segmentation.ipynb
├── ifood_df.csv
├── README.md
│
├── images/
│   ├── elbow_method.png
│   ├── customer_segments_income_vs_spending.png
│
├── outputs/
│   ├── clustered_customers.csv
│   ├── segment_summary.csv
