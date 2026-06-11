# Student_performance_prediction_system
Machine Learning project that analyzes student academic data and predicts student performance using classification and regression models.
# 🎓 Student Performance Prediction System

## 📌 Project Overview

The Student Performance Prediction System is a Machine Learning project that analyzes student academic data and predicts overall performance using classification and regression techniques.

The project includes Data Cleaning, Exploratory Data Analysis (EDA), Statistical Analysis, Classification Models, and Regression Models to identify factors affecting student performance.

---

## 🎯 Objectives

* Analyze student academic performance data.
* Discover patterns and relationships between CPI and SPI.
* Predict student performance categories (High, Medium, Low).
* Predict future CPI values using regression techniques.
* Generate insights to help improve student outcomes.

---

## 📊 Dataset Features

* Student ID
* Current CPI
* Current SPI
* Current Semester
* City Name
* Other academic attributes

---

## 🔍 Task 1: Data Cleaning & EDA

### Data Preprocessing

* Handled missing values.
* Replaced categorical missing values using Mode.
* Replaced numerical missing values using Mean.
* Removed duplicate records.
* Selected relevant features.

### Exploratory Data Analysis

* Histogram and Boxplot for CPI and SPI.
* Average CPI comparison across cities.
* Scatter Plot between CPI and SPI.
* Top 10 and Bottom 10 students based on CPI.

### Key Findings

* Most students fall into the medium performance category.
* Students with higher SPI generally have higher CPI.
* Wankaner showed the highest average CPI.

---

## 📈 Task 2: Statistical Analysis

### Methods Used

* Descriptive Statistics
* Karl Pearson Correlation
* T-Test
* IQR Outlier Detection
* Ranking & Percentile Analysis

### Results

* Strong positive correlation between SPI and CPI.
* No significant CPI difference between Rajkot and Jetpur.
* Identified 14 outliers using IQR.

---

## 🤖 Task 3: Machine Learning Models

### A. Classification Models

Models Used:

1. Decision Tree Classifier
2. Random Forest Classifier

Target Classes:

* High
* Medium
* Low

Evaluation:

* Accuracy Score
* Classification Report
* Confusion Matrix

Result:
Random Forest performed better because it reduces overfitting and provides more reliable predictions.

---

### B. Regression Model

Model Used:

* Linear Regression

Input Features:

* Current SPI
* Current Semester
* City

Target:

* Current CPI

Performance:

* RMSE = 0.70
* R² Score = 0.897

The model predicts student CPI with high accuracy.

---

## 💡 Insights

### Patterns Found

* Strong positive relationship between SPI and CPI.
* Location has minimal impact on student performance.

### Recommendations

* Provide mentoring and extra classes for low-performing students.
* Encourage regular study habits.
* Use rewards and feedback systems to improve engagement.

### Interesting Findings

* Current SPI is the most important feature for predicting CPI.
* City/location contributes very little to prediction accuracy.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---


## 👩‍💻 Author

Vidhi Ranpura

MSc Data Science Student

Marwadi University
