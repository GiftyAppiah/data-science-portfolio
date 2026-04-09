## 🎓 Student Score Analyzer

## 📌 Project Overview
This project analyzes student academic performance using Python. The dataset was intentionally designed with real-world issues such as missing values, inconsistent formatting, and outliers to simulate practical data cleaning and analysis scenarios.

The goal is to clean the data, perform analysis, and generate meaningful insights about student performance.

---

## 📥 Data Loading
The dataset containing 200 student records was loaded into a Pandas DataFrame from an Excel file.

---

## 🧹 Data Cleaning
- Removed extra spaces from column names and text values  
- Standardized student names using title casing  
- Converted score columns into numeric format  
- Handled inconsistent formatting in score entries  

---

## ❗ Handling Missing Values
Missing values in subject scores were handled using a hybrid approach:
- First, missing values were filled using each student's average score across available subjects  
- Remaining missing values were filled using column mean values  

---

## 🚨 Outlier Detection
Outliers were identified as unrealistic score values (above 100).  
These values were replaced with null values to maintain data integrity before analysis.

---

## ⚙️ Feature Engineering
New features were created to enhance analysis:
- Total Score = sum of all subject scores  
- Average Score = mean performance per student  
- Grade classification based on average score  

---

## 🏆 Ranking
Students were ranked based on their average scores to identify top performers and students needing improvement. Performance categories were also created for better grouping.

---

## 📊 Insights
- ICT recorded the highest average performance among all subjects  
- Mathematics showed relatively lower performance compared to other subjects  
- A small group of students consistently outperformed others across all subjects  
- Performance distribution shows a clear gap between top and average students  

---

## 🚀 Conclusion
This project demonstrates practical data cleaning, transformation, and analysis skills using Python. It reflects real-world data science workflows including handling messy data, feature engineering, and generating actionable insights.
