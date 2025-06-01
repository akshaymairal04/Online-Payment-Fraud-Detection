# 🛡️ Online Payment Fraud Detection

This project uses machine learning techniques to detect fraudulent online payment transactions. By training and evaluating multiple classification algorithms, the goal is to build an effective fraud detection system that can distinguish between genuine and fraudulent transactions.

## 📁 Project Structure

Online_Payment_Fraud_Detection/
│
├── Online_Payment_Fraud_Detection.ipynb # Main Jupyter Notebook
├── dataset/ # Directory for storing datasets
│ └── fraudTrain.csv / fraudTest.csv # Sample dataset (you must add these)
├── README.md # Project overview and usage guide


## 📊 Dataset

You can use any suitable dataset (e.g., the [Fraud Detection dataset from Kaggle](https://www.kaggle.com/datasets)). The notebook assumes a CSV with transaction details including features like amount, transaction type, time, etc., and a fraud label.

## 🧠 ML Algorithms Used

- Logistic Regression
- Random Forest
- XGBoost
- CatBoost
- SVM
- Decision Tree
- SGD Classifier

## ⚙️ Features

- Exploratory Data Analysis (EDA)
- Data Preprocessing (encoding, scaling)
- Handling class imbalance (SMOTE/undersampling)
- Model training and evaluation
- Cross Validation
- Confusion Matrix, Accuracy, Precision, Recall, F1-Score, ROC Curve
- 

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix


