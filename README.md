# 🚢 Titanic Survival Data EDA – Python Project

## 📌 Overview

This project performs an **Exploratory Data Analysis (EDA)** on the classic **Titanic dataset** using **Python (Pandas, Matplotlib, Seaborn)**. The goal is to analyze the passenger data and uncover insights about survival patterns, passenger demographics, class-wise distributions, and more using various **visualizations** and **data wrangling techniques**.

---

## 📁 Dataset Information

- **File Name:** `Titanic.csv`
- **Source:** Kaggle / OpenML
- **Records:** 891 passengers
- **Features include:**
  - `Survived`: 0 = No, 1 = Yes  
  - `Pclass`: 1 = First, 2 = Second, 3 = Third  
  - `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

---

## 🧪 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Key Explorations

### ✅ 1. Initial Data Understanding

- `.head()`, `.tail()`, `.shape`, `.columns`, `.info()`, `.describe()`
- Checked data types, missing values, and column names

---

### ✅ 2. Survival Analysis

- **Pie chart** showing survival vs non-survival
- Grouped by gender, class, and age (< 30 female survival rate)

📊 **Examples:**
```python
plt.pie(df['Survived'].value_counts(), labels=['Not Survived', 'Survived'], autopct='%1.1f%%')

