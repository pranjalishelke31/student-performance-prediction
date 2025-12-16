# 🎓 Student Performance Prediction

## 📌 Project Overview
This project predicts a student's final performance score using machine learning based on:
- Weekly self-study hours
- Attendance percentage
- Class participation

## 🎯 Objective
To analyze student academic data and build a regression model that predicts total score.

## 📊 Dataset Features
- weekly_self_study_hours
- attendance_percentage
- class_participation
- total_score (target)

## 🧠 Model Used
- Linear Regression

## 📈 Results
- Mean Absolute Error (MAE): ~7
- R² Score: ~0.66

This means the model explains around 66% of the variation in student scores.

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔮 Sample Prediction
A student studying 18 hours/week with 90% attendance and participation score of 6 is predicted to score around **89**.

## 📂 Project Structure

student-performance-project/
│
├── data/
│ └── student_data.csv
├── notebooks/
│ └── analysis.ipynb
├── models/
├── README.md
└── requirements.txt

## 🚀 Future Improvements
- Try other models like Random Forest
- Add more student features
- Build a web app for predictions
