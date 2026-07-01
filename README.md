# WalkRun-Activity-Classification
An end-to-end Machine Learning project for Human Activity Recognition (HAR) that classifies whether a person is walking or running using wearable motion sensor data. Includes Exploratory Data Analysis (EDA), data preprocessing, feature engineering, model training, evaluation, and comparison of multiple classification algorithms

# Walk vs Run Activity Classification using Machine Learning

## Project Overview

Human Activity Recognition (HAR) is an important application of Machine Learning that identifies physical activities performed by a person using data collected from wearable sensors. In this project, a predictive model is developed to classify whether a person is **Walking** or **Running** based on motion sensor readings collected from a smartwatch or wearable device.

The dataset contains raw readings from accelerometer and gyroscope sensors recorded while different users performed daily activities. The project follows the complete Machine Learning pipeline, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and comparison of multiple classification algorithms.

## Objectives

- Perform comprehensive Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Handle missing values and duplicates
- Analyze relationships between sensor features
- Train multiple classification models
- Compare model performance using evaluation metrics
- Select the best model for production deployment

## Dataset Features

- Date
- Time
- Username
- Wrist
- Activity (Target Variable)
- Acceleration X
- Acceleration Y
- Acceleration Z
- Gyroscope X
- Gyroscope Y
- Gyroscope Z

## Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes (Optional)

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Preprocessing
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Best Model Selection
10. Conclusion

## Result

After comparing multiple machine learning algorithms, the best-performing classification model is selected based on its accuracy, precision, recall, F1-score, ROC-AUC score, and overall generalization performance. This model is recommended for production use.
