
<h1 align="center">💼 HR Salary Prediction using Machine Learning</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" alt="Status Badge">
  <img src="https://img.shields.io/badge/ML-Type-Regression-blue" alt="ML Type Badge">
  <img src="https://img.shields.io/badge/Python-3.9-blue.svg" alt="Python Version">
</p>

---

## 📌 Project Overview

This project aims to **predict employee salaries** based on various features such as experience, job role, and department using a **Linear Regression** model. It showcases how machine learning can help HR departments make data-driven decisions.

> 📈 Suitable for beginner to intermediate ML learners working with regression models and real-world datasets.

---

## 🧾 Table of Contents

- [📁 Dataset Info](#dataset-info)
- [📊 EDA (Exploratory Data Analysis)](#eda)
- [📚 Libraries Used](#libraries-used)
- [🧠 Model Building](#model-building)
- [📈 Evaluation Metrics](#evaluation-metrics)
- [🧪 How to Run](#how-to-run)
- [🔮 Future Improvements](#future-improvements)
- [🧑‍💻 Author](#author)

---

## 📁 Dataset Info

| Feature Name     | Description                          |
|------------------|--------------------------------------|
| Experience       | Years of work experience             |
| Role             | Employee job role                    |
| Department       | HR, Tech, Sales, etc.                |
| Education Level  | Bachelor's, Master's, etc.           |
| Gender           | Male / Female                        |
| Salary           | Target Variable (₹ Monthly)          |

📦 *Dataset is included in this repository.*

---

## 📊 EDA

Key insights obtained from data:

- Salary increases with **experience**
- Some departments like **Tech** tend to have higher salaries
- Role and education also impact income

### 📉 Sample Visualizations:

<p align="center">
  <img src="images/experience_vs_salary.png" width="400" alt="Experience vs Salary">
  <img src="images/department_vs_salary.png" width="400" alt="Department vs Salary">
</p>

---

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_squared_error, r2_score
