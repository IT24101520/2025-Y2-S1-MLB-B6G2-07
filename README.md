# 2025-Y2-S1-MLB-B6G2-07
# Customer Churn Prediction Project

## 1. Project Overview
Telecom companies lose millions of dollars every year due to customer churn (customers leaving the service). Acquiring new customers is **5 times more expensive** than retaining existing ones.  

**Goal:** Predict which customers are likely to churn so that the company can proactively offer discounts, promotions, or better services to retain them.

**Problem Statement:**  
- **Input:** Customer data including demographic and usage information.  
- **Output:** Prediction of churn (`YES` for churned, `NO` for retained).

---

## 2. Dataset Details

| Feature | Description |
|---------|-------------|
| **Dataset Name** | Telco Customer Churn Prediction |
| **Source** | [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) |
| **Size** | 7043 customer records (rows) & 21 features (columns) |
| **Target Variable** | Churn: `YES` (customer left) / `NO` (customer retained) |

**Notes on Data Quality:**  
- Check for missing values in each column using `df.isnull().sum()`.  
- Identify duplicate rows using `df.duplicated().sum()`.  
- Handle missing or duplicate values as part of data cleaning.

---

## 3. Group Member Roles

| Member ID | Role |
|-----------|------|
| IT24102374 | Data Cleaning (handle missing/duplicate values, correct data types) |
| IT24101376 | Encoding categorical variables |
| IT24101551 | Outlier removal |
| IT24101536 | Normalization/Scaling |
| IT24101325 | Feature Selection |
| IT24101520 | Dimensionality Reduction |

---

## 4. How to Run the Code

1. **Clone the repository or download the notebook.**  
2. **Install required packages:**
3. **Encode categorical variables.**
4. **Handle outliers**
5. **Normlaize and scale**
6. **Feature Selection**
7. **Apply dimentionality reduction**
8. **Apply visualizations using matplotlib and seaborn**
```bash
pip install pandas numpy scikit-learn matplotlib seaborn

