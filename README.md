# Customer Churn Analysis — KPI Impact Study

## Project Overview
This project analyzes which business metrics actually predict customer churn and which commonly tracked KPIs are misleading.

The goal is to challenge assumptions and identify the variables that truly impact customer retention.

---

## Business Question
Which customer metrics are actually predictive of churn?

---

## Dataset
Source: Telecom customer dataset  

Variables include:
- Age
- Tenure
- Usage Frequency
- Support Calls
- Payment Delay
- Total Spend
- Last Interaction
- Churn (target)

---

## Methodology
1. Data loading and inspection
2. Cleaning and validation
3. Exploratory Data Analysis (EDA)
4. Correlation analysis
5. Visualization using heatmaps
6. Business interpretation of results

---

## Key Findings

### Strong predictors of churn
- Support Calls → positive correlation
- Payment Delay → positive correlation
- Total Spend → negative correlation

### Weak predictors
- Usage Frequency
- Tenure

---

## Insight
Many companies focus heavily on usage metrics assuming they predict loyalty.  
However, this dataset shows that **customer friction signals** are much stronger predictors of churn.

---

## Business Recommendations
Companies should prioritize monitoring:

- customer complaints
- payment behavior
- engagement quality

instead of focusing only on usage metrics.

---

## Tech Stack
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## Author
Denisse Pareja  
Data Analyst | Healthcare + Business Analytics

---

## Repository Structure
```
Churn_KPI/
│
├── data/
├── notebooks/
│   └── churn_analysis.ipynb
├── outputs/
└── README.md
```

---

## How to Run
```
pip install pandas matplotlib seaborn
jupyter notebook
```

Open notebook and run all cells.

---

## Project Type
Portfolio Project — Exploratory Data Analysis + Business Insight
