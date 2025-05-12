# 🏥 Healthcare Data Analysis and Visualization Project

## 📌 Overview
This project analyzes healthcare data to:
- Predict test results
- Assess readmission risks
- Segment patients
- Evaluate doctor performance
- Conduct cost-effectiveness analysis

The analysis integrates **machine learning techniques** with **data visualization** to provide comprehensive insights into healthcare patterns and efficiency.

---

## 📂 Dataset

**File**: `healthcare_dataset.csv`

**Features**:
- **Patient Demographics**: `Age`, `Gender`, `Blood Type`
- **Medical Details**: `Medical Condition`, `Date of Admission`, `Discharge Date`
- **Hospital Info**: `Doctor`, `Hospital`, `Room Number`
- **Financial Data**: `Billing Amount`, `Insurance Provider`
- **Treatment Outcomes**: `Medication`, `Test Results`

---

## 🛠 Requirements

Install core and optional dependencies with:

```bash
# Core dependencies
pip install pandas numpy scikit-learn xgboost matplotlib seaborn

# Optional for advanced visualization
pip install plotly tableauth
```

---

## 📁 Project Structure

```
healthcare-analytics/
├── data/
│   ├── raw/                   # Original datasets
│   └── processed/             # Cleaned data
├── notebooks/
│   ├── 1_Data_Preprocessing.ipynb
│   ├── 2_Predictive_Modeling.ipynb
│   └── 3_Advanced_Analysis.ipynb
├── src/
│   ├── preprocessing.py       # Data cleaning functions
│   └── models.py              # ML model implementations
├── results/
│   ├── visualizations/        # Charts and graphs
│   └── reports/               # Analysis summaries
└── tableau/                   # Dashboard files
```

---

## 📊 Dataset Overview

- **Rows**: 55,500 records  
- **Columns**: 15 fields  
- **Missing Values**: None detected  
- **Ideal for**: Categorical and group-based analysis (e.g., `Gender`, `Blood Type`, `Medical Condition`, `Test Results`)

---

## 💻 Advanced Analysis Tasks

- 🔍 Predictive Modeling for **Test Results** (Multi-class classification)
- 📉 Readmission **Risk Scoring**
- 👥 **Patient Segmentation** via clustering
- 🩺 Doctor **Performance Metrics**
- 💰 **Cost-Effectiveness** comparison by treatment and insurance type

---

## 🔑 Key Findings

- 🩺 **Hypertension and Diabetes** account for **52%** of all cases  
- ⚠️ **Cancer patients** show **62%** abnormal test results  
- 💰 **Medicare** billing is on average **15% higher** than other insurers  
- 🏥 **Emergency admissions** generate **2.3× more revenue** than elective cases  

---

## 🧰 Troubleshooting

**Common Issues:**
- 🗓 **Date Format Errors**: Ensure `YYYY-MM-DD` format  
- 🕳 **Missing Values**: Run `data_check()` utility to detect gaps  
- 🐍 **Package Conflicts**: Use a virtual environment with **Python 3.8+**

---

## 📈 Tableau Dashboard

Interactive Tableau dashboards are located in the `/tableau` folder and provide visual insights across:
- Admission types
- Medical condition patterns
- Test result distributions
- Financial comparisons
- Trends Over Time


<img width="993" alt="dashboard healthcare" src="https://github.com/user-attachments/assets/0db4311d-f8e2-48da-a272-8b6cd7eae597" />

---

## 📬 Contact

For questions, reach out to the project owner: **[gigishan@bu.edu]**
