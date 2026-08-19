# Stroke Prediction Using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to predict the likelihood of stroke based on patient-related health and demographic information.

The project explores the dataset, performs data preprocessing, encodes categorical variables, and builds a Logistic Regression model for stroke prediction.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset

The dataset contains **5,110 records and 12 columns** with information related to patients.

Some of the features include:

- Gender
- Age
- Hypertension
- Heart disease
- Ever married
- Work type
- Residence type
- Average glucose level
- BMI
- Smoking status
- Stroke

## 🔎 Data Preprocessing

The following preprocessing steps were performed:

- Inspected the dataset and its structure
- Checked for missing values
- Analyzed the distribution of stroke cases
- Filled missing BMI values using the mean
- Removed the `id` column
- Converted categorical variables into numerical values using Label Encoding
- Divided the dataset into training and testing sets

The dataset was split into:

- **80% Training Data**
- **20% Testing Data**

## 🤖 Machine Learning Model

A **Logistic Regression** model was used for binary classification.

The model predicts whether a patient is likely to have experienced a stroke based on the available features.

## 📈 Result

The Logistic Regression model achieved an accuracy of approximately:

**93.93%**

> Accuracy alone may not fully represent model performance because the dataset contains significantly more non-stroke cases than stroke cases.

## 📁 Project Files

stroke-prediction-ml/
│
├── Stroke_Prediction.ipynb
├── healthcare-dataset-stroke-data.csv
├── README.md
└── requirements.txt
