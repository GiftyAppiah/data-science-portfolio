#  Student Score Analyzer

## 📌 Project Overview

This project analyzes student academic performance using Python.
The dataset contains intentional inconsistencies such as missing values, extra spaces, inconsistent text formatting, and outliers to simulate real-world data challenges.

The goal is to clean, process, and analyze the data to extract meaningful insights about student performance.

---

## 🎯 Objectives

* Clean messy real-world data using Pandas
* Handle missing values and incorrect data types
* Analyze student performance across subjects
* Identify top-performing and struggling students
* Visualize trends using Matplotlib

---

## 🛠 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Excel

---

## 📂 Dataset Description

The dataset contains 200 student records with the following fields:

* Student_ID
* Name (inconsistent formatting)
* Gender
* Math
* English
* Science
* ICT

### Data Issues Introduced:

* Missing values
* Extra spaces in numeric fields
* Mixed uppercase/lowercase names
* Outlier values (e.g., score of 150)

---

## 🧹 Data Cleaning Process

* Removed extra spaces from column names and values
* Converted score columns to numeric format
* Handled missing values using mean imputation
* Standardized name formatting
* Detected and handled outliers

---

## 📊 Analysis Performed

* Computed total and average scores
* Assigned grades based on performance
* Identified top 5 students
* Identified bottom 5 students
* Calculated average performance per subject

---

## 📈 Visualizations

* Bar chart showing average scores per subject

(Add your chart screenshot here)

---

## 💡 Key Insights

* ICT recorded the highest average performance
* Math showed relatively lower performance compared to other subjects
* A few extreme values (outliers) were detected and corrected
* Performance varies significantly across students

---

## 📁 Project Structure

```
01-student-score-analyzer/
│
├── student_scores.xlsx
├── analysis.py
├── cleaned_student_data.xlsx
└── README.md
```

---

## 🚀 Conclusion

This project demonstrates the ability to handle messy datasets, perform data cleaning, and generate insights using Python. It reflects real-world data analysis workflows and builds a strong foundation for more advanced data science projects.

---
