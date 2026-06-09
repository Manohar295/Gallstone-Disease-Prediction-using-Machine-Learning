# Gallstone Prediction Using Logistic Regression

## Project Overview

This project focuses on predicting the presence of gallstones using Machine Learning techniques. The objective is to build a classification model that can accurately determine whether a patient has gallstones based on various body composition and health-related attributes.

## Problem Statement

Gallstones are a common health condition that can lead to serious complications if not detected early. The goal of this project is to develop a predictive model that assists in identifying gallstone cases using patient data.

## Dataset

The dataset contains demographic, health, and body composition parameters, including:

* Body Mass Index (BMI)
* Total Body Water (TBW)
* Extracellular Water (ECW)
* Intracellular Water (ICW)
* Total Body Fat Ratio (TBFR)
* Lean Mass (LM)
* Protein Percentage
* Mineral Percentage
* Skeletal Muscle Mass (SMM)
* Comorbidity Information
* Gallstone Status (Target Variable)

## Project Workflow

1. Data Collection and Loading
2. Data Exploration and Analysis
3. Data Cleaning and Preprocessing
4. Feature Selection
5. Correlation Analysis
6. Model Building using Logistic Regression
7. Model Evaluation
8. Performance Analysis

## Machine Learning Model

Several approaches were explored during experimentation. Among the tested models, **Logistic Regression achieved the best performance**, providing the most reliable and consistent results for this dataset.

### Model Performance

* Training Accuracy: **85.19%**
* Cross Validation Score: **80.74%**
* Testing Accuracy: **82.14%**

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Conclusion

The Logistic Regression model demonstrated strong predictive capability for gallstone detection and outperformed other experimented approaches. The model achieved over **82% test accuracy**, making it a suitable baseline solution for gallstone prediction and healthcare analytics applications.

## Future Improvements

* Experiment with advanced ensemble models.
* Perform hyperparameter tuning.
* Apply feature engineering techniques.
* Deploy the model as a web application using Flask or Streamlit.
