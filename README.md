## Diabetes Classification using Naive Bayes

This project aims to predict whether a person has diabetes based on various medical attributes using a **Naive Bayes** 
The dataset includes several health indicators such as glucose level, blood pressure, BMI, and family history of diabetes.

## Dataset Description

The dataset consists of the following columns:
- **Pregnancies** — Number of times the patient has been pregnant
- **Glucose** — Plasma glucose concentration
- **BloodPressure** — Diastolic blood pressure (mm Hg)
- **SkinThickness** — Triceps skinfold thickness (mm)
- **Insulin** — 2-Hour serum insulin (mu U/ml)
- **BMI** — Body Mass Index (weight in kg / height in m²)
- **DiabetesPedigreeFunction** — Likelihood of diabetes based on family history
- **Age** — Age of the patient
- **Diabetes** — Target variable (1 = has diabetes, 0 = no diabetes)

## Objective
To build a Naive Bayes model that classifies whether a person has diabetes or not using physiological and hereditary data.

## Workflow
-**Data Wrangling** — Load, assess, and clean the dataset.
- **Exploratory Data Analysis (EDA)** — Visualize data patterns and correlations.
- **Modeling** — Implemented Gaussian Naive Bayes using sklearn.naive_bayes.GaussianNB().
- **Evaluation** — Measure accuracy, precision, recall, and F1-score.

## Modeling Results
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|-----------|------------|---------|-----------|
| **Decision Tree (ID3)** | 75% | 76% | 75% | 76% |
| **Naive Bayes** | **81%** | **81%** | **81%** | **81%** |

✅ The **Naive Bayes model** outperformed the **Decision Tree (ID3)** with a **+6% improvement in accuracy**, demonstrating stronger generalization and better balance between precision and recall in predicting diabetes cases.
