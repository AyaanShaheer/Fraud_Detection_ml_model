# Fraud_Detection_ml_model
This project focuses on building a machine learning model to detect fraudulent transactions in financial datasets. Using a dataset containing over 6 million transactions, the project identifies and flags potential fraud by analyzing transaction patterns and customer behavior.

# **Fraud Detection Model for Financial Transactions**

## **Overview**
This project aims to develop a machine learning model to detect fraudulent transactions in a financial dataset. Using advanced data analysis and machine learning techniques, the project identifies patterns in the transaction data and flags potential fraud. The dataset contains over 6 million transactions, providing a comprehensive simulation of real-world financial activity.

---

## **Project Structure**

- **data/**: Folder containing the dataset in CSV format.
- **notebooks/**: Jupyter Notebooks used for model development and analysis.
- **models/**: Saved machine learning models.
- **scripts/**: Python scripts for data cleaning, feature engineering, and model evaluation.

---

## **Key Features**

- **Data Cleaning**: Addressed missing values, outliers (using Isolation Forest), and multi-collinearity to ensure data quality.
- **Feature Engineering**: Selected critical features such as transaction amount, account balances, and transaction types.
- **Fraud Detection Model**: Utilized Random Forest and Logistic Regression for predictive modeling.
- **Model Evaluation**: Employed confusion matrix, precision-recall curves, and AUC-ROC to demonstrate model performance.
- **Key Insights**: Provided factors that contribute to fraudulent transactions, including large cash-outs and abnormal balance shifts.

---

## **Data Dictionary**
The dataset contains the following columns:
- `step`: Time unit (1 hour = 1 step).
- `type`: Transaction type (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER).
- `amount`: Transaction amount.
- `nameOrig`: Customer initiating the transaction.
- `oldbalanceOrg`: Initial balance of the sender.
- `newbalanceOrig`: New balance of the sender.
- `nameDest`: Recipient customer.
- `oldbalanceDest`: Initial balance of the recipient.
- `newbalanceDest`: New balance of the recipient.
- `isFraud`: Whether the transaction is fraudulent.
- `isFlaggedFraud`: Transactions flagged due to large transfers (>200,000).

---

## **Installation Instructions**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fraud-detection
2. Navigate to Project Folder:
   ```bash
   cd fraud-detection
3. Install required python libraries
  ```bash
  pip install -r requirements.txt
```

---

Usage
1) Data Preprocessing: Run the Jupyter Notebook data_cleaning.ipynb to clean and preprocess the dataset.
2) Model Training: Use model_training.ipynb to train the fraud detection model.
3) Model Evaluation: Evaluate the model's performance using the evaluation metrics in model_evaluation.ipynb.


 

