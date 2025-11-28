

# Student Exam Score Predictor (UCI Dataset)

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Libraries](https://img.shields.io/badge/Libraries-pandas%20%7C%20scikit--learn%20%7C%20seaborn-green)
![Dataset](https://img.shields.io/badge/Dataset-UCI%20Student%20Performance-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

Predict the final math grade (G3) of students based on past performance, absences, study time, and support features.

---

## Overview

This project uses machine learning to predict students' **final math grades (G3)** based on several key factors:

- Previous grades (G1, G2)
- Study time per week
- Absences
- Past failures
- Family & school support
- Desire for higher education

- **Dataset**: UCI Student Performance (395 samples)
- **Model**: Random Forest Regressor  
- **Tools**: Python, pandas, seaborn, scikit-learn  
- **Author**: Yurii Dub (November 2025)

---

## Key Features

| Component | Description |
|----------|-------------|
| Data Loading | Directly from UCI URL |
| Feature Engineering | 8 selected features (studytime, failures, absences, G1, G2, famsup, schoolsup, higher) |
| Visualization | Feature importance bar plot |
| Model Performance | **R² = 0.829**, **MAE = 0.77** |
| Insights | G2 is the strongest predictor (~84% importance); absences also matter |

---

## Installation & Setup

1. Clone the repo:
```bash
git clone https://github.com/yuradubeducation-debug/Student-Exam-Score-Predictor.git
cd Student-Exam-Score-Predictor
