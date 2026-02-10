# Data Cleaning & Standardization of a Messy Sales Dataset

## 📌 Project Overview
This project demonstrates a complete data cleaning workflow applied to a real-world sales dataset.

Raw business data is often unreliable due to missing values, duplicates, inconsistent formatting, and incorrect data types.  
The goal of this project was to transform a messy dataset into a **clean, structured, and analysis-ready format**, while clearly documenting every decision made during the process.

This project reflects how data cleaning tasks are handled in real client and freelance scenarios.

---

## 📊 Dataset Information
- **Source:** Public dataset (Kaggle)
- **Type:** Sales / E-commerce data
- **Initial issues identified:**
  - Missing values in multiple columns
  - Duplicate records
  - Incorrect data types (numbers stored as text, dates as strings)
  - Inconsistent categorical values

---

## 🛠 Tools & Technologies Used
- Python
- pandas
- numpy
- Jupyter Notebook
- CSV files

---

## 🔍 Data Cleaning Process

The following steps were applied systematically:

### 1. Initial Inspection
- Reviewed dataset structure using `.info()` and `.head()`
- Identified missing values and data types
- Checked for duplicate rows

### 2. Handling Missing Values
- Numerical columns were handled using appropriate imputation methods (mean / median where reasonable)
- Categorical missing values were handled using placeholders such as `"Unknown"`
- Rows with insignificant or unusable data were removed when necessary

### 3. Duplicate Removal
- Exact duplicate rows were identified and removed to prevent data duplication and inaccurate analysis

### 4. Data Type Corrections
- Date columns converted to proper datetime format
- Numeric columns converted from text to numeric types
- Quantity and price fields standardized

### 5. Data Standardization
- Trimmed extra spaces
- Standardized categorical values to ensure consistency
- Ensured uniform formatting across columns

---

## ✅ Validation & Quality Checks
After cleaning:
- Missing values were resolved or reduced significantly
- All columns have correct data types
- No duplicate records remain
- Dataset is consistent and ready for analysis or reporting

Final validation checks were performed to ensure no unintended data loss occurred.

---

## 📦 Deliverables
- Cleaned CSV file (`cleaned_sales_data.csv`)
- Jupyter Notebook with documented cleaning steps
- Clear explanation of assumptions and decisions

---

## 🎯 Final Outcome
The final dataset is clean, reliable, and suitable for:
- Data analysis
- Reporting & dashboards
- Business decision-making
- Further modeling or research

This project showcases practical data cleaning skills commonly required in freelance and business environments.

---

## 👤 Author
**Haider Ali K.**  
Data Cleaning & Research Analyst  

