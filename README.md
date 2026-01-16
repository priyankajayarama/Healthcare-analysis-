# 🦠 Healthcare Data Analysis

**Domain:** Healthcare & Medical Analytics
**Tools:** Python, pandas, matplotlib, seaborn
**Output Format:** Jupyter Notebook (`.ipynb`)

---

## 📌 Project Overview

This project analyzes hospital and patient data to understand **patient demographics, medical conditions, hospital stay patterns, and healthcare cost drivers.**

The analysis focuses on:

* Patient profiles and medical conditions
* Hospital length of stay analysis
* Billing amount and cost distribution
* Admission type and insurance-based comparisons

All data cleaning, feature engineering, visualizations, and insights are fully contained inside the Jupyter Notebook.

📓 **Primary deliverable:**
`healthcare.ipynb`

---

## 🎯 Business Objectives

* Understand patient distribution across medical conditions
* Analyze healthcare cost patterns
* Identify factors impacting hospital stay duration
* Compare emergency, urgent, and elective admissions
* Generate insights for hospital operations and healthcare planning

---

## 📂 Project Structure

```
healthcare_analysis/
│
├── data/
│   └── healthcare_dataset.csv
│
├── notebooks/
│   └── healthcare.ipynb   ← All outputs here
│
└── README.md
```

---

## 🧾 Dataset Description

The dataset contains hospital admission records including:

* Patient demographics (age, gender, blood type)
* Medical condition
* Admission and discharge dates
* Hospital and doctor details
* Insurance provider
* Billing amount
* Admission type
* Medication and test results

Example fields:
`name, age, gender, blood_type, medical_condition, date_of_admission, discharge_date, hospital, insurance_provider, billing_amount, admission_type, medication, test_results`

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone <your-repository-link>
cd healthcare_analysis
```

### 2️⃣ Install required libraries

```
pip install pandas matplotlib seaborn
```

### 3️⃣ Open the notebook

```
jupyter notebook notebooks/healthcare.ipynb
```

Run all cells from top to bottom.

---

## 🧪 Data Validation Performed

The notebook includes:

* Missing value detection
* Duplicate record checks
* Date conversion and validation
* Length-of-stay calculation
* Billing amount and age range validation

All validation outputs are visible inside the notebook.

---

## 📊 Analysis Included in Notebook

* Descriptive statistics of patient and hospital variables
* Feature engineering (age groups, length of stay, high-cost cases)
* Cost analysis by condition and admission type
* Hospital stay duration analysis
* Insurance provider and medication distribution

---

## 📈 Visualizations Included

All charts are generated and displayed inside the notebook:

* Billing amount and stay duration box plots
* Patient count bar charts by condition and insurance provider
* Average billing comparison by admission type
* Age vs billing scatter analysis
* Stay duration vs cost relationship
* Healthcare correlation heatmap

---

## 💡 Business Insights & Conclusions

The notebook concludes with:

* Identification of high-cost medical conditions
* Hospital stay patterns by admission type
* Demographic and cost relationships
* Key operational insights for healthcare management

---

## 🏆 Skills Demonstrated

* Healthcare data cleaning and preprocessing
* Feature engineering
* Exploratory data analysis (EDA)
* Business-focused visualization
* Healthcare cost and operations analytics

---

## 👤 Author

**Name:** *Priyanka Jayarama*
**Role:** Aspiring Data Analyst
**Skills:** Python, pandas, SQL, Data Visualization

---

📌 *All charts, results, and conclusions are available inside the Jupyter notebook.*
