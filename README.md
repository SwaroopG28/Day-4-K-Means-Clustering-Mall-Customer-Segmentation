## 📊 **Day 4: K-Means Clustering – Mall Customer Segmentation**

### 📄 **Project Overview**
This project focuses on applying **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their shopping behavior. The dataset used is the **Mall Customer Segmentation Dataset** available on Kaggle.

**Dataset Link:** [Mall Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

### 🎯 **Objective**
- Segment customers into distinct groups based on their spending behavior and annual income.
- Use the **Elbow Method** to determine the optimal number of clusters.
- Visualize customer segments and analyze clustering results.

---

### 📊 **Dataset Description**
- **CustomerID:** Unique identifier for each customer (removed during preprocessing).
- **Gender:** Categorical feature (encoded numerically).
- **Age:** Age of the customer.
- **Annual Income (k$):** Customer's annual income.
- **Spending Score (1-100):** Customer's spending behavior score.


---

### 🛠️ **Steps Performed**

#### **1. Data Preprocessing**
- Removed `CustomerID` (non-informative feature).
- Encoded `Gender` using **LabelEncoder**.
- Selected relevant numerical features (`Annual Income`, `Spending Score`).
- Standardized features using **StandardScaler**.

#### **2. Exploratory Data Analysis (EDA)**
- Visualized feature distributions (`Age`, `Annual Income`, `Spending Score`).
- Scatter plots for `Annual Income` vs `Spending Score`.
- Pair plot analysis.

#### **3. Optimal Cluster Selection**
- Used the **Elbow Method** to determine the optimal number of clusters.
- Chose **k=5** as the optimal number of clusters.

#### **4. Model Training**
- Applied **K-Means Clustering** with `k=5`.
- Analyzed cluster centers and their distributions.

#### **5. Cluster Visualization**
- Scatter plot showing customer clusters.
- Pair plot highlighting cluster separation.

#### **6. Insights and Recommendations**
- Derived actionable insights from the customer clusters.

---

### 📊 **Results**
- **Optimal Number of Clusters:** 5 (determined using Elbow Method).
- **Key Insights:**
   - Cluster 0: High Income, Low Spending
   - Cluster 1: Low Income, High Spending
   - Cluster 2: Balanced Income and Spending
   - Cluster 3: Low Income, Low Spending
   - Cluster 4: High Income, High Spending

