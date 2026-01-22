# 🏎️ F1 Driver Performance Prediction Model

## 📌 Project Overview
This project focuses on analyzing historical Formula 1 race data to predict driver performance using statistical and machine learning techniques.  
The goal is to demonstrate end-to-end data analysis skills — from data cleaning and feature engineering to model building and result interpretation.

This is a portfolio project created to simulate a real-world analytics use case in sports analytics.

---

## 🎯 Objectives
- Analyze historical Formula 1 driver and race data
- Identify key factors influencing driver performance
- Build a predictive model to estimate driver performance
- Present insights through a simple web interface

---

## 🧠 Approach
1. **Data Collection & Cleaning**
   - Cleaned and structured race and driver datasets
   - Handled missing values and inconsistent records

2. **Feature Engineering**
   - Selected performance-related features such as qualifying position, grid position, and race history
   - Transformed raw data into model-ready format

3. **Modeling**
   - Built a regression-based prediction model
   - Evaluated model performance using standard metrics

4. **Application Layer**
   - Developed a lightweight Flask web app to display predictions

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Flask
- HTML / CSS
- SQLite

---

## 📊 Key Learnings
- Importance of feature selection in predictive modeling
- Translating raw sports data into structured analytical insights
- Building simple, interpretable models over complex black-box approaches
- Deploying analytics results via a web interface

---

## 🚀 Future Improvements
- Incorporate additional race-level features (weather, track conditions)
- Improve model performance with advanced feature engineering
- Add data visualizations for exploratory analysis
- Extend predictions across multiple seasons

---

📁 Repository Structure
f1-prediction-model/
│
├── data/
│   └── f1_datasets/                 # Raw and processed Formula 1 datasets
│
├── scripts/                         # Data cleaning, feature engineering, modeling
│
├── static/
│   └── images/                      # Images and visual assets for the web app
│
├── templates/                       # HTML templates for the Flask interface
│
├── app.py                           # Flask application entry point
├── f1_racing.db                     # SQLite database with processed race data
├── requirements.txt                 # Python dependencies
├── todo.txt                         # Development notes (optional)
└── README.md                        # Project documentation



