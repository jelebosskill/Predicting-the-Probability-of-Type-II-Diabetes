# Predicting the Probability of Type II Diabetes

## Introduction

The primary goal of this project is to develop a classification model that predicts the probability of an individual having Type II diabetes based on demographic and clinical factors.

The dataset consists of **100,000 rows** and **8 columns**, representing potential risk factors. The target variable is binary, indicating whether or not the individual has Type II diabetes.

---

## Dataset Variables

The dataset includes the following variables:  
1. **Sex**: Gender of the individual.  
2. **Age**: Age of the individual.  
3. **Hypertension**: Whether the individual has high blood pressure (1 = Yes, 0 = No).  
4. **Heart Disease**: Whether the individual has a history of heart disease (1 = Yes, 0 = No).  
5. **Smoking History**: Whether the individual has a history of smoking (categorical).  
6. **BMI**: Body Mass Index, a measure of body fat based on weight and height.  
7. **Glucose Levels**: Blood glucose level at the time of the test.  
8. **Glycemic Level**: Indicates glycemic control level.  

**Target Variable**:  
- **Diabetes**: Indicates the presence of Type II diabetes (1 = Yes, 0 = No).

---

## Project Goals

- **Data Cleaning and Preprocessing**: Handle missing values, encode categorical data, and normalize features.  
- **Feature Engineering**: Analyze feature importance to improve model accuracy.  
- **Model Development**: Train and test classification models to predict diabetes.  
- **Performance Evaluation**: Use metrics such as confusion matrix, ROC curve, precision, recall, and F1 score to evaluate the model's effectiveness.

---

## Installation

To run this project, you need to install the required Python libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
