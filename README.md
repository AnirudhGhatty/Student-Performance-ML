# Student-Performance-ML
A beginner Machine Learning project to predict student performance using regression models and real world academic data

# Overview
This project aims to predict a student's final grade using academic and behavioral factors such as study time , absences , failures and previous grades. The goal is to understand what factors decide the academic performance

# Dataset
Source : [UCI Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)
Records : 395 students
Features : 33 attributes including behavioral and academic data

# Methodology 
* Built a Linear Regression model using scikit-learn
* Evaluated model performance using the R² score
* Compared multiple features to analyze the prediction accuracy

# Models and results
🔹 Model 1: Behavioral Features Only
Features used :
Study Time
Absences
Failure

R² score : 0.0307
Interpretation : Behavioral factors alone provide very limited information to predict the final score

🔹 Model 2: Behavioral Features including previous test scores 
Features used :
Study Time
Absences
Failure
G1
G2

R² score : 0.7821
Interpretation : Including prior academic scores improves the prediction accuracy by a huge margin which shows that they are a major determinant in predicting the final grade

# Key Insights
* Prior grades (G1, G2) are the most influential predictors of final grade (G3)
* Behavioral features like study time and absences have limited standalone impact
* Model performance improved drastically (R²: 0.02 → 0.78) when academic history was included
* Highlights the importance of consistent academic performance over time

# Study time vs Final grade
