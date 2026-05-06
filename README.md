# Breast_Cancer-Prediction
Breast Cancer Prediction using machine learning techniques to classify tumors as malignant or benign based on medical diagnostic features. This project applies data preprocessing, feature selection, and classification algorithms to achieve accurate predictions.

# Overview
This project uses machine learning to detect breast cancer from patient diagnostic features

# Objective
To build a predictive model that can accurately identify patients at risk of breast cancer on clinical data.

# Dataset
Source: (Kaggle Custom dataset)

https://www.kaggle.com/datasets/mdnazmussadat1/breast-cancer 

# Feature Importance 

Using the Random Forest model, we identified key features influencing breast cancer diagnosis. The most impactful features include several tumor markers (CEA, CA125, CA153), blood indicators (Platelet_Count, WBC_Count, CRP, LDH), and patient characteristics (Age, Tumor_Size_mm, BMI).These insights highlight the critical factors associated with diagnosis in this dataset, offering potential avenues for further clinical investigation and targeted interventions.

<img width="1635" height="1030" alt="feature_importance" src="https://github.com/user-attachments/assets/968c72d5-9d20-4b84-83e2-2fe54eb4fd40" />

# Machine Learning Models

Among the evaluated models (Logistic Regression, SVM, Random Forest, XGBoost), **Logistic Regression** emerged as the best performer, achieving an AUC-ROC of   0.5948 and a test accuracy of 57.25%. Despite hyperparameter tuning and ensembling, overall model performance remained moderate, indicating potential for further feature engineering or advanced techniques.

<img width="2082" height="884" alt="model_comparison" src="https://github.com/user-attachments/assets/8ba75f0d-ddaa-4443-9283-141cccdfa051" />

# Result

Cross-Validation Accuracy 
The cross-validation analysis revealed the consistency and robustness of each model's performance across different data folds. Logistic Regression generally showed the highest mean cross-validation accuracy (58.77%), with SVM and Random Forest following closely. The spread of accuracies (indicated by the boxplots) suggests that Logistic Regression also performed relatively consistently across folds, indicating good generalization ability on unseen data within the training set. This reinforces its position as the top-performing model.

<img width="1482" height="883" alt="crossval_boxplot" src="https://github.com/user-attachments/assets/65ccb4d0-7dbf-4159-ba7b-4a16d12c97a3" />




