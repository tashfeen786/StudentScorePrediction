**Student Exam Score Prediction
\n
**Project Overview

This project focuses on predicting students' exam scores using different machine learning techniques. The goal is to identify the key factors (like study hours, attendance, sleep, motivation, etc.) that influence academic performance.

We explore Linear Regression, Polynomial Regression, and Multiple Features Regression models and compare their performance.

📂 Dataset

Source: Student Performance Factors Dataset (Kaggle)

Features in dataset:

Hours_Studied

Attendance

Parental_Involvement

Access_to_Resources

Extracurricular_Activities

Sleep_Hours

Previous_Scores

Motivation_Level

Internet_Access

Tutoring_Sessions

Family_Income

Teacher_Quality

School_Type

Peer_Influence

Physical_Activity

Learning_Disabilities

Parental_Education_Level

Distance_from_Home

Gender

Target: Exam_Score

🛠️ Tools & Libraries

Python

Pandas / NumPy → Data cleaning & preprocessing

Matplotlib / Seaborn → Visualization

Scikit-learn → Machine Learning Models (Linear Regression, Polynomial Regression, Evaluation Metrics)

🔎 Exploratory Data Analysis (EDA)

Handled missing values

Visualized relationships between study hours, attendance, and exam score

Built a correlation heatmap to identify strong predictors

📊 Findings from Correlation:

Attendance (0.58) → Strongest predictor of exam score

Hours Studied (0.45) → Significant impact

Previous Scores & Tutoring Sessions → Small impact

Sleep Hours & Physical Activity → Almost no relation

🤖 Model Training
1. Linear Regression

MAE: ~2.44

MSE: ~10.85

R²: ~0.23

2. Polynomial Regression

MAE: ~2.44

MSE: ~10.84

R²: ~0.23

3. Multiple Features Regression

MAE: ~1.35

MSE: ~5.33

R²: ~0.62 ✅

👉 Best performance was achieved with multiple features regression.

📊 Visualizations

Correlation Heatmap

Scatterplots (Study Hours vs Exam Score, Attendance vs Exam Score)

Prediction vs Actual plots

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/student-score-prediction.git
cd student-score-prediction


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook Student_Score_Prediction.ipynb

🏆 Future Improvements

Try Random Forest or XGBoost for better accuracy

Hyperparameter tuning

Feature engineering (interaction terms, dropping weak features)

Build a simple web app with Streamlit to allow users to input data and predict exam scores

✨ Results Summary

Attendance & Study Hours are the most important predictors

Multiple Features Regression performed best with R² ≈ 0.62

Strong potential to improve accuracy with advanced ML models

⚡ Author: Tashfeen Aziz
