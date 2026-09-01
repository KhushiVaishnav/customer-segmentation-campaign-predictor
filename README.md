# 🎯 Customer Segmentation & Campaign Response Prediction

> An end-to-end Data Science and Machine Learning project that analyzes customer behavior, identifies customer segments, and predicts campaign response to support targeted marketing decisions.

---

## 📌 Project Overview

This project analyzes customer demographics, spending behavior, and campaign interactions to answer two key business questions:

1. **Who are the customers?** → Customer segmentation using K-Means clustering.
2. **Who is likely to respond to a campaign?** → Campaign response prediction using Machine Learning.

The project covers the complete Data Science workflow, including data preprocessing, exploratory data analysis, feature engineering, customer segmentation, predictive modeling, and business-focused insights.

---

## 🎯 Business Problem

Marketing campaigns are often sent to a broad customer base, which can result in unnecessary spending and low response rates.

This project aims to:

- Identify meaningful customer segments based on behavior and spending patterns.
- Understand which segments are more likely to respond to campaigns.
- Build Machine Learning models to predict campaign response.
- Support more targeted and data-driven marketing strategies.

---

## 🛠️ Technologies Used

| Category | Tools |
|----------|-------|
| **Programming & Data Analysis** | Python, Pandas, NumPy |
| **Machine Learning** | Scikit-learn, Random Forest, Logistic Regression, Decision Tree |
| **Clustering** | K-Means, PCA |
| **Data Processing** | Feature Engineering, Missing Value Handling, Outlier Treatment, Scaling |
| **Model Optimization** | SMOTE, Cross-Validation, GridSearchCV, Hyperparameter Tuning |
| **Visualization** | Matplotlib, Seaborn |

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing

The dataset was prepared through:

- Missing-value handling
- Outlier treatment
- Duplicate analysis
- Removal of non-informative columns
- Encoding categorical variables
- Feature scaling

### 2️⃣ Feature Engineering

Created **15+ features** to capture customer behavior, including:

- Total Spending
- Purchase Behavior
- Campaign Engagement
- Campaign Success Rate
- Customer Value / CLV-related features

### 3️⃣ Customer Segmentation

K-Means clustering was used to identify **4 customer segments**:

| Segment | Customer Share | Response Rate |
|---------|--------------:|--------------:|
| 🏆 **Ultra Premium** | 12.8% | **40.7%** |
| 💎 Premium Spenders | 23.0% | 15.2% |
| 📊 Middle Class | 28.4% | 9.1% |
| 🛒 Budget Conscious | 35.8% | 11.0% |

The Elbow Method and Silhouette Score were used to evaluate the clustering approach, while PCA was used to visualize the resulting customer segments.

---

## 🤖 Campaign Response Prediction

Multiple Machine Learning models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

The Random Forest model achieved the strongest overall performance.

| Model | Accuracy | F1-Score | ROC-AUC |
|-------|----------|----------|---------|
| Logistic Regression | 82.8% | 0.536 | 0.823 |
| Decision Tree | 84.7% | 0.488 | 0.835 |
| **Random Forest** | **84.7%** | **0.558** | **0.879** |

### Model Improvement Techniques

- SMOTE for class imbalance
- Cross-Validation
- GridSearchCV
- Hyperparameter Tuning
- PCA experimentation

---

## 📊 Key Findings

- Identified **4 distinct customer segments**.
- Random Forest achieved **87.9% ROC-AUC**.
- Achieved an **F1-score of 55.8%**.
- The **Ultra Premium segment represented 12.8% of customers**.
- This segment had a **40.7% campaign response rate**, approximately **2.7× higher than average**.
- Campaign engagement and customer behavior features were among the most useful predictors of campaign response.

---

## 💡 Business Insights

The analysis suggests that marketing strategies can be improved by prioritizing customers with a higher predicted probability of response.

Potential benefits of targeted campaigns include:

- More efficient marketing budget allocation
- Higher campaign response rates
- Personalized strategies for different customer segments
- Better prioritization of high-value customers

The project also includes a targeting analysis to estimate how model-based targeting could improve marketing efficiency compared with targeting the entire customer base.

---

## 📁 Repository Structure

```text
customer-segmentation-campaign-predictor/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│   └── saved/
│
├── notebooks/
│   ├── 01_Data_Preprocessing.ipynb
│   ├── 02_Clustering_Segmentation.ipynb
│   └── 03_Prediction_Models.ipynb
│
├── reports/
│   ├── figures/
│   └── tables/
│
├── Customer_Segmentation_Report.pdf
└── README.md
```

---

## 🚀 Future Improvements

- Develop an interactive application for customer segmentation and prediction.
- Experiment with additional Machine Learning models.
- Automate the end-to-end preprocessing and prediction pipeline.
- Deploy the model for interactive use.

---

## 👩‍💻 Author

**Khushi Vaishnav**

Aspiring Data Scientist | Python • SQL • Machine Learning | Exploring AI & GenAI
