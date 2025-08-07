# 📊 Student Performance Dataset

This repository contains a dataset titled `exams.csv`, which captures demographic and academic performance data of students across various ethnic groups, parental education levels, and preparation statuses. It is designed to support exploratory data analysis (EDA), predictive modeling, and insights into educational equity.

---

## 📁 File Description

- **`exams.csv`**  
  A comma-separated file with the following columns:
  - `gender`: Student's gender (`male`, `female`)
  - `race/ethnicity`: Categorical groupings (e.g., `group A` to `group E`)
  - `parental level of education`: Education level of the student's parent/guardian
  - `lunch`: Type of lunch received (`standard`, `free/reduced`)
  - `test preparation course`: Completion status of a prep course (`completed`, `none`)
  - `math score`: Math exam score (0–100)
  - `reading score`: Reading exam score (0–100)
  - `writing score`: Writing exam score (0–100)

---

## 🎯 Project Objectives

This dataset can be used to:

- Perform **exploratory data analysis (EDA)** to uncover patterns in student performance.
- Build **predictive models** to estimate scores based on demographic and educational factors.
- Evaluate **fairness metrics** across different subgroups.
- Create **visual storytelling dashboards** using tools like Power BI or matplotlib/seaborn.

---

## 🧪 Suggested Analysis Ideas

- Correlation heatmaps to explore relationships between scores and categorical features.
- Feature importance analysis using regression or classification models.
- ROC curves and precision-recall metrics to evaluate model performance.
- Equity-focused breakdowns by race/ethnicity, gender, and lunch status.

---

## 🚀 Getting Started

To begin analysis:

```bash
# Load the dataset using pandas
import pandas as pd
df = pd.read_csv('exams.csv')


 