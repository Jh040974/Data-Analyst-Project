 # 📊 Student Performance in Exams — Capstone Project

This project analyzes student exam performance to uncover factors influencing academic outcomes and provide data-driven recommendations for educators and policymakers. Using a dataset of 1,000 students, we explore demographic, socioeconomic, and academic variables to identify patterns and actionable insights.

---

## 📁 Dataset Overview

- **Source**: [Kaggle - Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Records**: 1,000 students
- **Features**:
  - **Demographics**: Gender, Race/Ethnicity
  - **Socioeconomic**: Parental Education, Lunch Type
  - **Academic**: Test Preparation Course, Math/Reading/Writing Scores

---

## 🧪 Project Workflow

### 1. **Exploratory Data Analysis (EDA)**
- Assessed data completeness and structure
- Visualized distributions and outliers
- Analyzed score patterns by gender, race, parental education, lunch, and test prep

### 2. **Statistical Insights**
- Strong correlations between reading, writing, and math scores
- Socioeconomic indicators (lunch type, parental education) linked to performance
- Test prep completion significantly boosts scores

### 3. **Modeling**
- **Regression**: Predict math scores using linear regression
  - R² = 0.34, MAE ≈ 9.56
- **Classification**: Predict pass/fail using logistic regression
  - Accuracy = 90%
- **Random Forest**: Feature importance and ROC analysis for fairness and reliability

### 4. **Equity-Focused Recommendations**
- Flowchart maps data → model → policy triggers → targeted interventions:
  - 📚 Outreach Programs
  - 🏠 School-Family Bridges
  - 🥗 Nutrition Assistance
  - 🎯 Tutor Matching


## 📈 Key Visuals

- Boxplots, histograms, and heatmaps for score distributions
- Correlation matrices and feature importance charts
- ROC curve for pass/fail prediction
- Flowchart of data-driven policy interventions

All plots are saved in the `visuals/` folder for easy reference.


## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: pandas, matplotlib, seaborn, scikit-learn
- **Modeling**: Linear & Logistic Regression, Random Forest
- **Visualization**: Custom color palettes, annotated plots

# 🧠 What I Learned

- **Correlation ≠ Causation**: Socioeconomic indicators like lunch type and parental education show strong associations with scores, but deeper causal analysis is needed.
- **Modeling Trade-offs**: Regression models struggled to predict exact scores (R² ≈ 0.34), but classification models excelled at predicting pass/fail outcomes (Accuracy ≈ 90%).
- **Visualization Matters**: Thoughtful visual design (color palettes, layout, emoji-enhanced flowcharts) improves accessibility and storytelling.
- **Fairness Considerations**: Disparities in performance across demographic groups highlight the importance of equity-aware modeling and policy design.



## 🔄 What I’d Change

- **Feature Expansion**: Include additional variables like attendance, teacher ratings, or study habits to improve model accuracy.
- **Model Complexity**: Explore ensemble methods or neural networks for better score prediction.
- **Ethical Evaluation**: Incorporate fairness metrics (e.g., equal opportunity, disparate impact) to assess model bias across subgroups.
- **Interactive Dashboards**: Build a dashboard (e.g., with Plotly or Streamlit) to make insights more accessible to educators and stakeholders.

---

## 🚀 Next Steps

- Deploy models in a dashboard for real-time student risk assessment
- Collaborate with educators to design targeted interventions
- Extend analysis to other subjects or longitudinal performance data

---

## 📬 Contact

For questions, feedback, or collaboration opportunities, feel free to reach out via GitHub Issues.








---













 














`
 