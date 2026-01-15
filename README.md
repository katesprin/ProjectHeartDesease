# Heart Disease Prediction Using Exercise Heart Rate

## Project Overview
Heart disease is one of the leading causes of death worldwide. This project applies **statistical analysis and machine learning** to determine whether **maximum heart rate achieved during exercise** can predict the presence of heart disease, while controlling for **age and sex**.

The analysis uses the **Cleveland Heart Disease dataset** and demonstrates that exercise-based heart rate metrics are a **strong, independent predictor** of cardiovascular disease.

---

## Objectives
- Perform exploratory data analysis (EDA) on cardiovascular health indicators
- Test statistical differences in exercise heart rate by disease status
- Build logistic regression models for binary classification
- Evaluate model performance using ROC curves and AUC
- Interpret results 
---

## Files
- `HeartDisease Project.ipynb` — Main Jupyter Notebook containing all analysis
- `HeartDisease Project.html` — Rendered HTML report (recommended for viewing)
- `README.md` — Project documentation

## How to View
- **Best option:** Open `HeartDisease Project.html` in a web browser
- **GitHub preview:** View the notebook directly on GitHub
- **NBViewer:** Paste the notebook URL: https://github.com/katesprin/ProjectHeartDesease/blob/84137ed77410652d03a30fc6ea829feada355676/HeartDisease%20Project.ipynb into https://nbviewer.org for best rendering

---

## Methods & Techniques
- Exploratory Data Analysis (EDA)
- Welch Two-Sample *t*-Test
- Correlation Analysis
- Logistic Regression
- ROC Curve & AUC Evaluation

---

## Key Results
- Patients with heart disease achieved **significantly lower maximum heart rates**
- Welch *t*-test confirmed the difference was statistically significant (*p* < 0.001)
- Logistic regression findings:
  - Higher exercise heart rate → **lower odds of heart disease**
  - Male sex significantly increased disease risk
- **Final Model Performance:**  
  - **AUC = 0.79**, indicating good classification accuracy

---

## Visualizations
- Heart rate distributions and boxplots
- Predicted probability curves
- Correlation heatmap
- ROC curve comparing models

---

## Tools and Technologies
- R
- Jupyter Notebook
- tidyverse (ggplot2, yardstick)
- caret


---

## Author
Kate Nikitina
