# 🛒 Customer Segmentation & Strategic Targeting

## 📌 Executive Summary
A data analytics and machine learning project using **K-Means Clustering** and **PCA** on retail customer data (`Mall_Customers.csv`) to automatically group customers and generate targeted marketing strategies[cite: 4].

---

## 📸 Cluster Visualization

<p align="center">
  <img src="visuals/Income vs spending analysis cluster.png" width="48%" alt="Income vs Spending Cluster" />
  <img src="visuals/Customer analysis PCA1.png" width="48%" alt="PCA Cluster Distribution" />
</p>

---

## 🎯 Customer Segments & Business Strategies
The model uses dynamic median thresholds to automatically categorize customers into four key profiles[cite: 4]:

* **VIP / High Value:** High Income + High Spending → *Strategy:* Exclusive rewards & luxury previews[cite: 4].
* **High Income / Low Spenders:** High Income + Low Spending → *Strategy:* Personalized upsells & recommendations[cite: 4].
* **Impulsive Spenders:** Low Income + High Spending → *Strategy:* Flash sales & trend notifications[cite: 4].
* **Budget Conscious:** Low Income + Low Spending → *Strategy:* Value discounts & essential deals[cite: 4].

---

## ⚙️ How It Was Built
1. **Data Preprocessing:** Handled categorical encoding (`LabelEncoder`) and feature scaling (`StandardScaler`)[cite: 4].
2. **Model Optimization:** Evaluated **Silhouette Scores** to automatically pick the best number of clusters ($K$)[cite: 4].
3. **PCA Mapping:** Applied 2D **Principal Component Analysis** for accurate visual plotting[cite: 4].
4. **AI-Assisted Workflow:** Utilized **Gemini Prompt Engineering** to accelerate code generation, optimize logic, and clean the pipeline[cite: 4].

---

## 🛠️ Tools & Tech Stack
* **Language:** Python[cite: 4]
* **AI Tool:** Google Gemini (Prompt Engineering)
* **Libraries:** `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`[cite: 4]
