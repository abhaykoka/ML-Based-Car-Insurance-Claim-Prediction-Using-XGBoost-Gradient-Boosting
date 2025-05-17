# ML-Based-Car-Insurance-Claim-Prediction-Using-XGBoost-Gradient-Boosting
Project Description:
This project focuses on building a robust machine learning pipeline to predict whether a car insurance customer is likely to file a claim, using gradient-boosted decision trees via XGBoost. The goal is to assist insurance providers in identifying high-risk customers, enabling smarter policy decisions, reduced fraudulent claims, and optimized customer engagement.

The solution incorporates end-to-end steps from data preprocessing to model deployment, including:

 Data cleaning & preprocessing: Handling missing values, encoding categorical features, and scaling numeric data.

 Exploratory data analysis (EDA): Understanding patterns in customer behavior and risk profiles.

 Feature engineering: Creating and selecting features that impact claim likelihood.

 Modeling with XGBoost: Gradient boosting classifier with Stratified K-Fold cross-validation for reliable performance estimates.

 Evaluation: AUC-ROC, confusion matrix, classification report, and SHAP explainability to interpret feature impact.

 Experiment tracking with MLflow: Logging parameters, metrics, and trained models for reproducibility and comparison.

This project demonstrates both predictive performance and explainability, bridging the gap between machine learning and real-world business impact.

Why should we use XG boost?
XGBoost was used in this project for its high performance and efficiency in classification tasks. It offers advanced regularization, handles missing values well, and supports early stopping to prevent overfitting. Its ability to handle large datasets and deliver fast, accurate results made it an ideal choice for modeling car insurance claim predictions.

Why should we used mlflow?
MLflow was used in this project to track and manage machine learning experiments efficiently. It enabled automatic logging of parameters, metrics, and models during each fold of cross-validation, ensuring reproducibility and easy comparison of results. MLflow also supported organized experiment tracking and model versioning, making the training process more transparent and streamlined.

