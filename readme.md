# Spine Condition Classification

This project utilizes machine learning models to predict whether a person's spine condition is normal or abnormal based on physical measurements of the spine. It aims to aid in identifying individuals at risk of lower back pain (LBP) using easily obtainable physical data.

## Dataset
The dataset consists of 310 patient records, each with 12 numerical features representing various physical characteristics of the spine. The target variable is binary, indicating whether the condition is **normal** or **abnormal**. The features include:
- Pelvic incidence
- Pelvic tilt
- Lumbar lordosis angle
- Sacral slope
- Pelvic radius
- Degree of spondylolisthesis
- Pelvic slope
- Direct tilt
- Thoracic slope
- Cervical tilt
- Sacrum angle
- Scoliosis slope

## Objectives
- Preprocess the dataset, handle missing values, and standardize the features.
- Train multiple classification models, including Logistic Regression, Support Vector Classifier, Decision Tree, and Random Forest, to predict the spine condition.
- Evaluate model performance based on accuracy.
- Use model predictions to classify spine conditions as normal or abnormal.

## Steps
1. Load and preprocess the dataset.
2. Perform exploratory data analysis (EDA) to understand the distribution and relationships between features.
3. Train multiple machine learning models using the processed data.
4. Evaluate the models' accuracy on the test set.
5. Visualize and compare the results.
