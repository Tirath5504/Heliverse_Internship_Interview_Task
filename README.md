# Heliverse Internship Task Documentation

## Introduction
This document outlines an internship task completed as part of the selection process for an AI internship at Heliverse. The task involves analyzing a dataset related to employee attrition and building predictive models to classify attrition risk using various machine learning algorithms.

## How to Run the File

To run the file, you have two options:

1. **Google Colab**:
   - Import the `heliverse-intern-task.ipynb` file into Google Colab.
   - Import the Kaggle dataset from [here](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).
   - Click on the 'Run All Cells' button to execute the code.

2. **Kaggle**:
   - View the notebook on my Kaggle account [here](https://www.kaggle.com/code/tirathbhathawala/heliverse-intern-task?rvi=1).

## Code Overview
The provided code is a Jupyter Notebook file (`heliverse-intern-task.ipynb`) containing Python code executed in a Google Colab environment. The notebook utilizes several libraries commonly used in data science and machine learning tasks, including NumPy, Pandas, Matplotlib, Seaborn, Plotly Express, and scikit-learn.

## Dataset
The dataset used in this task is sourced from the IBM HR Analytics Employee Attrition & Performance dataset. The data includes various attributes of employees such as age, education, job satisfaction, and performance ratings, along with a binary label indicating whether the employee has churned (attrition) or not.

## Tasks Completed
1. **Importing and Preprocessing Dataset**: Initial exploration of the dataset, checking for missing values and data types, and preprocessing steps like encoding categorical variables.

2. **Exploratory Data Analysis (EDA)**: Exploring relationships between variables through visualizations like line plots, bar plots, and heatmaps.

3. **Model Building**:
    - **Logistic Regression**: Building a logistic regression model to predict employee attrition.
    - **Support Vector Machine (SVM)**: Implementing an SVM classifier with hyperparameter tuning using GridSearchCV.
    - **Decision Tree**: Constructing a decision tree classifier with hyperparameter tuning.
    - **Random Forest**: Building a random forest classifier with hyperparameter tuning.
    - **XGBoost**: Utilizing the XGBoost algorithm with feature importance analysis.

4. **Model Evaluation**: Evaluating model performance using metrics such as accuracy, classification reports, confusion matrices, and ROC-AUC scores.

5. **Comparing Model Performance**: Comparing the performance of different machine learning models using ROC-AUC scores and visualizing the results.

## Conclusion
The completed tasks demonstrate proficiency in data preprocessing, exploratory data analysis, and machine learning model building and evaluation. The documentation provided herein serves to summarize the code, methodology, and outcomes of the internship task, showcasing my skills and understanding in AI and machine learning.
