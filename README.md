# Student Placement Prediction Using Machine Learning

## Project Overview

This project uses machine learning to predict student placement outcomes based on academic performance, technical skills, internships, projects, and other student-related factors.

The goal is to explore student placement data, identify relevant patterns, compare classification models, and build a prediction system for new student profiles.

## Dataset Information

- Dataset: Student Placement Prediction Dataset 2026
- Total records: 100,000
- Input features used: 23
- Target variable: `placement_status`
- Target classes: Placed and Not Placed

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Project Workflow

1. Data loading and exploration
2. Data quality checks
3. Exploratory Data Analysis (EDA)
4. Feature selection
5. Categorical feature encoding
6. Train-test split (80:20)
7. Feature scaling
8. Model training
9. Model evaluation
10. Feature importance analysis
11. Model saving and loading
12. Prediction for new student profiles

## Machine Learning Models

The following classification algorithms were tested:

- Logistic Regression
- Balanced Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 56.98% |
| Balanced Logistic Regression | 55.785% |
| Random Forest | 55.17% |
| Gradient Boosting | 56.645% |

The original Logistic Regression model achieved the highest test accuracy among the models evaluated.

## Prediction System

A prediction function was developed to accept 23 student details and predict:

- Placement status
- Probability of being placed
- Probability of not being placed

The system was tested with both an existing student record and a new sample student profile.

## Model Deployment Preparation

The trained model and preprocessing information were saved using Joblib.

Saved file:

`student_placement_model.joblib`

The saved model was successfully loaded and tested again.

## Key Learning Outcomes

- Data cleaning and preprocessing
- Exploratory data analysis
- Categorical encoding
- Feature scaling
- Classification model training
- Model evaluation and comparison
- Feature importance analysis
- Model persistence using Joblib
- Building a prediction function

## Limitations

The best-performing model achieved 56.98% test accuracy. The current predictive performance is limited, and the model should be treated as an educational project rather than a reliable real-world placement decision system.

## Future Improvements

- Improve predictive performance through feature engineering.
- Perform hyperparameter tuning.
- Experiment with additional machine learning algorithms.
- Test on independent real-world placement data.
- Develop an interactive application using Streamlit.

## Author

Shanti Kantamreddy
