# Heart Disease Prediction Using Logistic Regression

## Overview

Heart disease is one of the leading causes of death worldwide. Early detection and prediction of heart disease are crucial for better prevention and treatment. This project uses **Logistic Regression**, a machine learning algorithm, to predict the likelihood of a patient developing heart disease within ten years, based on health and lifestyle factors.

This project is implemented in **Python** and is suitable for running on **Google Colab** or any local Python environment.

---

## Dataset

The dataset is derived from an ongoing cardiovascular study in Framingham, Massachusetts. It contains **over 4,000 patient records** with multiple features, including:

- Age
- Gender
- Smoking habits
- Total cholesterol
- Systolic blood pressure
- Glucose levels
- Other health indicators

**Target variable:**  
`TenYearCHD` → 1 if the patient developed coronary heart disease within 10 years, 0 otherwise.

> The dataset can be downloaded [here](https://www.kaggle.com/datasets/amanajmera1/framingham-heart-study-dataset).

---

## Features Used

The model uses the following **6 features**:

| Feature      | Description                           |
|-------------|---------------------------------------|
| age         | Age of the patient                     |
| Sex_male    | Gender (Male=1, Female=0)             |
| cigsPerDay  | Number of cigarettes smoked per day   |
| totChol     | Total cholesterol (mg/dL)             |
| sysBP       | Systolic blood pressure (mmHg)        |
| glucose     | Blood glucose level (mg/dL)           |

---

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies using:

```bash
pip install -r requirements.txt
