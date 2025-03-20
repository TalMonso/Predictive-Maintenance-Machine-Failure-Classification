# Predictive-Maintenance-Machine-Failure-Classification
⚙️ Predictive Maintenance: Machine Failure Classification

📌 Overview

This project aims to classify machine failures based on provided sensor data. The dataset was obtained from a Kaggle competition, and various data preprocessing, exploratory data analysis (EDA), and machine learning techniques were applied to improve classification accuracy.

📊 Dataset

The dataset contains information about machine conditions, with binary labels:

✅ 0 - Machine is functioning properly

❌ 1 - Machine has a failure

The dataset is highly imbalanced, with over 100,000 functional machines and only slightly more than 2,000 faulty machines.

🛠 Methodology

🧹 Data Preprocessing:

🗑 Removed unnecessary columns (id, Product ID)

🏗 Handled missing values and outliers

⚖️ Addressed class imbalance using oversampling techniques

📈 Exploratory Data Analysis (EDA):

📊 Visualized class distribution

🔗 Analyzed correlation between features

🔍 Identified key predictive variables

🤖 Model Training & Evaluation:

Implemented various machine learning models such as:

📊 Logistic Regression

🌲 Random Forest

🚀 XGBoost

🏆 Evaluated model performance using accuracy, precision, recall, and F1-score

🔧 Applied hyperparameter tuning for optimization

✅ Conclusions

The dataset presented a class imbalance challenge, which was mitigated using oversampling techniques.

🚀 XGBoost performed the best among the tested models, achieving the highest accuracy and recall.

🔍 Feature importance analysis revealed that certain sensor readings were strong indicators of potential failures.
