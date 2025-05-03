# Final-Projects

# 🔍 LinkedIn Job Trend Analysis

This project provides a simple but insightful analysis of job demand trends across roles and cities by parsing and visualizing a sample dataset inspired by LinkedIn job postings. It highlights the most in-demand skills per city and per role.

## 📦 Dataset Overview

The dataset contains job postings across various cities with associated roles and skill requirements. It includes:

- **Job Title**
- **Location**
- **Skills** (comma-separated)

**Sample Roles Covered:**
- Data Scientist
- Software Engineer
- Data Analyst
- Machine Learning Engineer
- Backend Developer
- Full Stack Developer
- Data Engineer

**Sample Cities:**
- New York
- San Francisco
- Austin

## 📊 Features

### ✅ Skill Demand Heatmap
Visualizes the top 10 most in-demand skills by city.

### ✅ Skill vs Role Matrix
Shows how frequently each skill appears across different job roles.

### ✅ Skill Recommendations
Suggests key skills for each role based on aggregated data.

## 📂 Files Included

- `job_trend_report.pdf` – A complete analysis report with heatmaps and charts.
- `job_postings.csv` – The raw dataset.
- `Linkedln Job Trend Analysis.py` – Python script to generate visuals.
- `README.md` – This file.

## 🛠️ Tools Used

- Python
  - Pandas
  - Seaborn
  - Matplotlib
- Jupyter Notebook



# 🧮 Customer Lifetime Value (LTV) Prediction

This project predicts the **Customer Lifetime Value (LTV)** using transactional data from an online retail store. The goal is to support data-driven marketing strategies by segmenting customers based on their predicted future value.

---

## 📌 Objective

To build a regression model that estimates customer LTV using features derived from historical purchase behavior.

---

## 🛠️ Tools & Technologies

- Python, Pandas, NumPy
- Scikit-Learn, XGBoost
- Seaborn, Matplotlib
- Jupyter Notebook
- Excel (data source)

---

## 📂 Dataset

The dataset used is the **Online Retail Dataset** from the UCI Machine Learning Repository.  
It contains ~540,000 transactions from a UK-based online retailer between 2010 and 2011.

---

## 📈 Features Engineered

- `recency`: Days since last purchase
- `tenure`: Days between first and last purchase
- `frequency`: Total number of unique purchases
- `aov`: Average Order Value
- `monetary`: Total revenue generated (used as target)

---

## 📊 Modeling Approach

1. **Data Cleaning**: Removed returns, null customers, and negative values
2. **Feature Engineering**: Recency, Frequency, Monetary, AOV
3. **Model**: XGBoost Regressor
4. **Evaluation Metrics**:
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
5. **Customer Segmentation**: Low / Medium / High LTV groups using quantiles

---

## 📁 Files in Repository

| File | Description |
|------|-------------|
| `Customer Lifetime Value Prediction.ipynb` | Jupyter notebook |
| `Online Retail.xlsx` | Input dataset |
| `README.md` | Project documentation |

---

## 📊 Visualizations

- Feature importance (XGBoost)
- LTV distribution (histogram)
- Segment-wise LTV comparison (boxplot)

---

