# Student Exam Score Predictor (UCI Dataset)

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Libraries](https://img.shields.io/badge/Libraries-pandas%20%7C%20scikit--learn%20%7C%20seaborn-green)
![Dataset](https://img.shields.io/badge/Dataset-UCI%20Student%20Performance-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

Quick Run: Open in Google Colab (no installation needed!)
---

**Predict final math grade (G3)** using study time, failures, absences, and family support.  
*My first Data Science project — self-taught in 3 weeks! Built in <100 lines of code.*

---

## Overview

This project uses machine learning to predict students' **final math grades (G3)** based on key factors:
- Study time per week
- Past failures
- Absences
- Family & school support
- Desire for higher education

- **Dataset**: [UCI Student Performance](https://archive.ics.uci.edu/dataset/320/student+performance) (395 students, Portuguese schools)
- **Model**: Random Forest Regressor
- **Tools**: Python, pandas, seaborn, scikit-learn
- **Created**: November 2025 by **Yurii Dub**  
  *(Self-taught using YouTube, Kaggle and AI + free datasets)*

Explore how data science can predict educational outcomes!

---

## Key Features

| Feature | Description |
|---------|-------------|
| Data Loading | Directly from UCI URL |
| Feature Engineering | Selected 8 key columns (e.g., studytime, failures) |
| Visualization | Correlation heatmap + feature importance bar plot |
| Model Performance | **R² ≈ 0.92** (as shown in plots), **MAE ≈ 1.2** |
| Insights | Previous grades (G2) dominate; extra study boosts scores |

---

## Installation & Setup

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yuradubeducation-debug/Student-Exam-Score-Predictor.git
   cd Student-Exam-Score-Predictor

2. Install dependencies:
bashpip install pandas numpy matplotlib seaborn scikit-learn

3. Run the notebook:
bashjupyter notebook "UCI_Student_Performance (2).ipynb"

Quick Run: Open in Google Colab (no installation needed!)
