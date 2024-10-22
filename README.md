# Classifier Comparison for Liver Disease Prediction
# Overview
This project compares the performance of three different classifiers: Support Vector Machine (SVM), Logistic Regression, and Random Forest, to determine which model yields the best results in terms of accuracy, precision, recall, and F1 score for predicting liver disease.

# Dataset
The dataset used for this analysis is the Indian Liver Patient Records, which is available on [Kaggle](https://www.kaggle.com/uciml/indian-liver-patient-records). This dataset contains information about liver patients, including various medical attributes that can help predict the presence or absence of liver disease.

# Dataset Features:
 # Age: Age of the patient
 # Gender: Gender of the patient (Male/Female)
 # Total Bilirubin: Total bilirubin level in the blood
 # Direct Bilirubin: Direct bilirubin level in the blood
 # Alkaline Phosphatase: Alkaline phosphatase level in the blood
 # Alanine Aminotransferase (ALT): ALT level in the blood
 # Aspartate Aminotransferase (AST): AST level in the blood
 # Total Proteins: Total proteins in the blood
 # Albumin: Albumin level in the blood
 # Albumin and Globulin Ratio: Ratio of albumin to globulin
 # Liver Disease: Target variable indicating whether the patient has liver disease (1) or not (0)

# Methodology
1. # Data Preprocessing:
    Load the dataset and handle missing values.
    Encode categorical variables.
    Split the data into training and testing sets.
2. # Model Training:
     Train three classifiers: 
     Support Vector Machine (SVM)
     Logistic Regression
     Random Forest
     Fine-tune model parameters using cross-validation.
3. # Model Evaluation:
    Evaluate each model using metrics such as:
      Accuracy
      Precision
      Recall
      F1 Score
      Compare the results to identify the best-performing classifier.
# Conclusion
Based on the evaluation metrics, the best classifier for predicting liver disease will be determined. The results highlight the strengths and weaknesses of each model in the context of this dataset.
# Usage
 To execute the analysis and view the results run in the Jupyter Notebook (or Python script)
