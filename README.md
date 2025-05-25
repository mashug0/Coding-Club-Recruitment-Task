# Coding-Club-Recruitment-Task

# Task 1: CampusPulse - Coding Week 2025 Submission 🎓💞

## 📌 Project Overview
CampusPulse explores the factors influencing whether students are in romantic relationships, using demographic, academic, and lifestyle data.

built a classification model to predict relationship status and analyzed the underlying behavioral patterns using machine learning and SHAP.

---

## 📂 Structure

| File | Description |
|------|-------------|
| `Dataset\\Dataset.csv` | Cleaned student dataset |
| `Dataset\\Dataset.docx`| Description of the dataset used|
| `source.ipynb` | Code for Levels 1–5 |
| `README.md` | Project summary |
---

## 🔍 Levels Completed

### ✅ Level 1 & 2: Data Cleaning and Imputation  
- We Identified 
    `Feature_1` : `Age` 
    `Feature_2` : `studytime`
    `Feature_3` : `Time spent boozing with friends`

- Handled missing values via median/mode strategies  
- Encoded categorical and binary fields

### ✅ Level 3: Exploratory Insight Report  
- Boxplots, violin plots, scatterplots, and radar plots were used to analyze behavior and lifestyle traits

### ✅ Level 4: Prediction Model  
- **Model:** Random Forest  
- **Accuracy:** 62%  
- **Top Features:** `G2`, `G3`, `Age`, `absenses`

### ✅ Level 5: SHAP Interpretation  
- SHAP bar chart shows lifestyle behaviors dominate predictions  
- Individual predictions explained via SHAP waterfall plots

---
## 🛠 Tech Stack
- Python, pandas, seaborn, scikit-learn, SHAP, matplotlib

---

## 📧 Contact
For queries or feedback: saksham.gupta@iitg.ac.in
