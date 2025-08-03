# Fraud-Detection-in-Banking-Data
The increasing use of digital banking services—such as online bank transfers, credit card transactions, and UPI payments—has made financial systems more vulnerable to fraud. Detecting these fraudulent activities in real time is crucial for protecting individuals and organizations from significant financial losses.

This project presents a machine learning-based fraud detection system that analyzes transactional data across three key domains:

Bank Account Transactions
Credit Card Transactions
UPI (Unified Payments Interface) Payments
Each domain is powered by trained ML models to classify transactions as legitimate or fraudulent based on features such as transaction amount, time, device ID, location, and more.

The project is implemented as an interactive web application using Streamlit, and it is designed for end users such as bank customers, financial analysts, and small businesses. It features user authentication via Supabase, cloud deployment on AWS or Hugging Face Spaces, and provides a smooth interface for testing real-world or sample data for fraud risk.

📦 Datasets Used
Bank Account Fraud Dataset
Kaggle Link

Credit Card Fraud Detection Dataset
Kaggle Link

UPI Transaction Dataset
Kaggle Link

Features
🔐 User Signup/Login System (via Supabase)
📊 Real-time Fraud Detection for:
Bank Account Transactions
Credit Card Transactions
UPI Payments
📁 Upload and test transaction CSV files
🧠 ML Model Inference using 6 trained .pkl models
📈 Interactive Results Display using Streamlit
☁️ Cloud Deployment (AWS / Hugging Face Spaces)
ML Models Used
Preprocessing Techniques: Label Encoding, Scaling
Algorithms Used:
Random Forest
Logistic Regression
XGBoost
Evaluation Metrics:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Each domain has two trained models, stored as .pkl files, to ensure high-performance real-time inference.

Use Cases
🧾 Individuals: Analyze personal transaction data
🏪 Small Businesses: Monitor UPI-based payments for fraud
Technologies Used
Python
Pandas, NumPy, Scikit-learn, XGBoost
Streamlit (Frontend + UI)
Supabase (Auth + Database)
Cloud: AWS
