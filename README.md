# AI-Triage System for Symptom-Based Diagnosis

A machine learning solution for automating emergency department triage classification to improve patient prioritization and reduce waiting times.

## 📌 Project Summary
This project develops an AI-based triage system that classifies patients into appropriate urgency levels based on symptoms and medical data. Traditional manual triage systems often lead to delays, overcrowding, and inconsistent assessments. Our solution addresses these issues through machine learning models that provide faster, and more accurate patient prioritization.

## ⚙️ Key Details

### Dataset
- **Source:** [Harvard Dataverse — doi:10.7910/DVN/7SOYC7](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/7SOYC7)
- **Size:** 2,205 patient records with 67 features  
- **Target:** `Triage Level` (3 urgency levels)

### Models Implemented
- Random Forest (**best performer**)  
- Support Vector Machine  
- Logistic Regression  
- Gaussian Naive Bayes

### Results
Random Forest outperformed other models with:
- **61%** test accuracy  
- Highest performance across all triage levels  


## 🚀 Quick Start

### Prerequisites
- Python
- Jupyter Notebook

## Contributors
| Name           | Contributions                                                                 |
|------------------------|-------------------------------------------------------------------------------|
| Abdulrhman Albusaad    | Exploratory Data Analysis (EDA)                                             |
|                        | Handling missing data and data quality issues                               |
|                        | Support Vector Machines (SVM)                                               |
| Ali Assuleiteen        | Exploratory Data Analysis (EDA)                                             |
|                        | Dealing with different value types                                          |
|                        | Feature Engineering                                                          |
|                        | Gaussian Naive Bayes                                                        |
| Mahdi Alzakari         | Exploratory Data Analysis (EDA)                                             |
|                        | Feature Engineering                                                          |
|                        | Logistic Regression                                                         |
| Waeeil Alessa          | Exploratory Data Analysis (EDA)                                             |
|                        | Handling missing data and data quality issues                               |
|                        | Hypotheses Formulation                                                      |
|                        | Random Forest                                                               |
