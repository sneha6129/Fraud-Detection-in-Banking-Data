#  Fraud Detection in Banking Data

The increasing use of digital banking services—such as online bank transfers, credit card transactions, and UPI payments—has made financial systems more vulnerable to fraud. Detecting these fraudulent activities in real time is crucial for protecting individuals and organizations from significant financial losses.

This project presents a **machine learning-based fraud detection system** that analyzes transactional data across three key domains:

- **Bank Account Transactions**
- **Credit Card Transactions**
- **UPI (Unified Payments Interface) Payments**

Each domain is powered by trained ML models to classify transactions as **legitimate** or **fraudulent** based on features such as transaction amount, time, device ID, location, and more.

The project is implemented as an interactive **web application using Streamlit**, and it is designed for end users such as **bank customers, financial analysts, and small businesses**. It features **user authentication via Supabase**, cloud deployment on **AWS** or **Hugging Face Spaces**, and provides a smooth interface for testing real-world or sample data for fraud risk.

## 📦 Datasets Used

- **Bank Account Fraud Dataset**  
  [Kaggle Link](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022)

-  **Credit Card Fraud Detection Dataset**  
  [Kaggle Link](https://www.kaggle.com/datasets/kartik2112/fraud-detection/data)

  - **UPI Transaction Dataset**  
  [Kaggle Link](https://www.kaggle.com/datasets/iamravi11/fraud-upi-transaction-details)


##  Features

- 🔐 User Signup/Login System (via Supabase)
- 📊 Real-time Fraud Detection for:
  - Bank Account Transactions
  - Credit Card Transactions
  - UPI Payments
- 📁 Upload and test transaction CSV files
- 🧠 ML Model Inference using 6 trained `.pkl` models
- 📈 Interactive Results Display using Streamlit
- ☁️ Cloud Deployment (AWS / Hugging Face Spaces)


##  ML Models Used

- **Preprocessing Techniques**: Label Encoding, Scaling
- **Algorithms Used**:
  - Random Forest
  - Logistic Regression
  - XGBoost
- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

Each domain has two trained models, stored as `.pkl` files, to ensure high-performance real-time inference.

##  Use Cases

- 🧾 Individuals: Analyze personal transaction data
- 🏪 Small Businesses: Monitor UPI-based payments for fraud

## Technologies Used

- Python
- Pandas, NumPy, Scikit-learn, XGBoost
- Streamlit (Frontend + UI)
- Supabase (Auth + Database)
- Cloud:  AWS


<img width="792" height="418" alt="image" src="https://github.com/user-attachments/assets/c70e70a1-5827-41fc-9e23-ee664b422181" />
![Picture2](https://github.com/user-attachments/assets/c0958bc6-7f23-44cf-8cde-57e899ddddc4)
![Picture3](https://github.com/user-attachments/assets/51a97873-f05c-4bcf-8f25-862368031a51)
![Picture4](https://github.com/user-attachments/assets/f5c4f274-0113-4dc9-9b0a-9f8acf3bceb2)
![Picture5](https://github.com/user-attachments/assets/e14405d3-362a-4797-bede-f6807cb60604)
![Picture6](https://github.com/user-attachments/assets/a7f84b76-d442-4c07-a4c4-d2d0696d1ddb)
![Picture7](https://github.com/user-attachments/assets/d03a6cd0-9bc7-44d0-a819-7a8be485176d)
![Picture8](https://github.com/user-attachments/assets/1aeeb784-a675-4715-9bad-e8aaed28113a)
![Picture9](https://github.com/user-attachments/assets/09a39ada-cdb1-47d5-adf3-d00df91962b1)
![Picture10](https://github.com/user-attachments/assets/ce86b71d-ad21-41d7-8e07-edfad7e125b0)
![Picture11](https://github.com/user-attachments/assets/468a7369-e332-4b40-8642-c155f0fa54c0)
![Picture12](https://github.com/user-attachments/assets/c90709d0-8531-48b8-9cd2-bf83665c44a4)












