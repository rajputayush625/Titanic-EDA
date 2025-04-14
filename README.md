# 🚢 Titanic Survivability Analysis – Exploratory Data Analysis (EDA)

## 📌 Overview

This repository contains a full Exploratory Data Analysis (EDA) of the Titanic dataset using Python. The analysis covers data cleaning, visualization, feature engineering, and a basic logistic regression model to predict passenger survival.

This project was completed as part of a **Data Analyst Internship Task (Task 5)**.

---

## 📁 Files Included

| File                     | Description                                      |
|--------------------------|--------------------------------------------------|
| `Final_Titanic_EDA.ipynb` | Jupyter Notebook with full EDA and model       |
| `titanic_train.csv`       | Titanic training dataset used in the analysis  |
| `Final_Titanic_PDF.pdf`   | Exported PDF version of the notebook           |

---

## 🧪 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Key Highlights

- **Data Cleaning**: Missing values handled using imputation and column dropping.
- **Visualizations**:
  - Countplots showing survival distribution by gender and class.
  - Histograms for Age and Fare distributions.
  - Heatmaps for null values.
  - Boxplots for age imputation based on class.
- **Feature Engineering**:
  - Converted categorical variables to numeric using dummy encoding.
  - Dropped irrelevant or redundant features.
- **Modeling**:
  - Logistic Regression used to predict survival.
  - Achieved ~80% accuracy on the test set.

---

## 📌 Summary of Insights

- Female passengers and those in higher classes had better survival chances.
- Younger passengers generally had higher survival rates.
- Ticket fare had a slight positive correlation with survival.
- The `Cabin` column had excessive missing data and was dropped.
