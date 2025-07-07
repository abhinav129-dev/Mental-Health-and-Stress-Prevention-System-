# Mental-Health-and-Stress-Prevention-System-

# 🧠 Mental Health and Stress Prevention System

## 1. 📝 Problem Statement
Mental health issues are often recognized too late, leading to severe consequences. The objective of this project is to build a system that analyzes lifestyle patterns, behavioral signals, and work-related stress to predict stress levels and mood trends, allowing early interventions to prevent mental health deterioration.

---

## 2. 🎯 Aim of the Project
To develop a predictive system that:
- Classifies stress levels (Low, Medium, High)
- Calculates a mood score based on behavioral indicators
- Recommends preventive actions
- Outputs results in CSV format for further tracking and analysis

---

## 3. 🏗️ Architecture

```text
Daily Inputs 
    ↓
Stress Analysis (Growing_Stress, Changes_Habits, Coping_Struggles)
    ↓
Risk Assessment (Mood Pattern Score)
    ↓
Preventive Intervention Matching
    ↓
Progress Monitoring (Predicted Labels + CSV Output)
``` 
4. 🧩 Model Structure
Preprocessing: Handles missing values, encodes categorical data, scales features.

Stress Assessment: Random Forest Classifier predicts stress level.

Pattern Recognition: Random Forest Regressor estimates mood score.

Intervention Matching: Rule-based recommendations generated from predictions.

Monitoring: Outputs predictions and advice in a structured .csv file.

5. 📊 Dataset Used
File Name: Mental Health Dataset.csv

Features Include:

Demographics: Gender, Country, Occupation

Lifestyle: Days Indoors, Coping_Struggles, Work_Interest

Mental Health Factors: Growing_Stress, Mood_Swings, family_history

Output targets: Derived Stress_Level and Mood_Score

Dataset cleaned and preprocessed before modeling. 
Dataset source Link: (https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset?resource=download)

