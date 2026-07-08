💳 Credit Card Fraud Detection using Machine Learning
📌 Project Overview

This project implements a Credit Card Fraud Detection System using Machine Learning algorithms to classify transactions as either fraudulent or legitimate. The model is trained on a real-world credit card transaction dataset from Kaggle and compares the performance of multiple classification algorithms.

The project includes data preprocessing, exploratory data analysis (EDA), feature encoding, model training, evaluation, visualization, and model serialization for future deployment.

🎯 Objectives
Detect fraudulent credit card transactions.
Compare the performance of different Machine Learning models.
Visualize transaction patterns and fraud distribution.
Save the best-performing model for deployment in a user interface.
📂 Dataset

Source: Kaggle – Fraud Detection Dataset

The dataset contains transaction details such as:

Transaction Amount
Merchant
Category
Gender
City Population
Geographic Information
Transaction Time
Fraud Label (is_fraud)

Target Variable:

0 → Legitimate Transaction
1 → Fraudulent Transaction
⚙️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
📊 Project Workflow
Load Dataset
      │
      ▼
Data Exploration
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Data Cleaning
      │
      ▼
Label Encoding
      │
      ▼
Feature Selection
      │
      ▼
Model Training
(Logistic Regression,
Decision Tree,
Random Forest)
      │
      ▼
Model Evaluation
      │
      ▼
Model Comparison
      │
      ▼
Feature Importance
      │
      ▼
Save Best Model
🤖 Machine Learning Models

The following algorithms were implemented and compared:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier

Each model was evaluated using multiple performance metrics.

📈 Evaluation Metrics

The models were evaluated using:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Confusion Matrix

These metrics provide a comprehensive assessment of the model's fraud detection performance, particularly for the imbalanced nature of fraud datasets.

📊 Data Visualization

The project includes several visualizations to better understand the dataset:

Fraud vs Legitimate Transaction Distribution
Transaction Amount Distribution
Fraud by Gender
Fraud by Merchant Category
Correlation Heatmap
Confusion Matrix
Feature Importance Graph
💾 Model Saving

The best-performing model is saved using Joblib as:

fraud_model.pkl

This allows the trained model to be reused without retraining.

📁 Project Structure
Credit_Card_Fraud_Detection/
│
├── fraudTrain.csv
├── fraudTest.csv
├── fraud_detection.py
├── fraud_model.pkl
├── app.py
├── README.md
└── requirements.txt

Dataset:
Download fraudTrain.csv and fraudTest.csv from Kaggle and place them in the project root before running the notebook.
link- https://www.kaggle.com/datasets/kartik2112/fraud-detection
🚀 Future Improvements
Develop an interactive Streamlit web application.
Improve model performance using feature engineering.
Handle class imbalance using techniques such as SMOTE.
Perform hyperparameter tuning for improved accuracy.
Deploy the application on Streamlit Cloud or another hosting platform.
📌 Conclusion

This project demonstrates how machine learning can be applied to identify fraudulent credit card transactions by analyzing transaction patterns. Multiple classification algorithms were evaluated, with the best-performing model saved for future deployment. The project showcases the complete machine learning workflow, from data preprocessing and exploratory analysis to model training, evaluation, and deployment readiness.
