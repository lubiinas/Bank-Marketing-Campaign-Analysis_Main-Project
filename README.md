# Bank Marketing Campaign Analysis
This project presents an end-to-end machine learning pipeline built to analyze and predict customer responses in a bank's marketing campaign using the UCI Bank Marketing Dataset. It includes thorough data preprocessing, feature engineering, model building, evaluation, and deployment-ready pipelines.

📁 Dataset
Source: UCI Machine Learning Repository

Data Description: Contains customer and campaign-related attributes from a Portuguese bank’s telemarketing campaigns.

Objective: Predict whether a client will subscribe to a term deposit (y - binary classification).
🧪 Key Features
EDA: Outlier detection (Boxplots), skewness correction (Box-Cox), correlation heatmaps, class distribution.

Preprocessing:

One-hot encoding for categorical features

Skewness treatment

Standard scaling

Model Building:

Compared 5 models: Logistic Regression, Random Forest, SVM, KNN, Decision Tree

Hyperparameter tuning via GridSearchCV

Model Evaluation:

Accuracy, precision, recall, F1-score, confusion matrix

R² score for regression task (campaign duration)

Model Saving: Models and pipelines saved using joblib for deployment readiness.

✅ Results
Best classification model: Random Forest

Achieved 80%+ accuracy on test data

Final models are saved and ready for inference
