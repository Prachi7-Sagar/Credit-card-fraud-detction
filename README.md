# 💳 Credit Card Fraud Detection using Machine Learning

This project builds a machine learning model to detect fraudulent credit card transactions using a real-world anonymized dataset. It handles severe class imbalance, performs detailed exploratory data analysis (EDA), and applies classification models to identify fraud effectively.

---

## 📁 Dataset

- **File**: `bank.csv`
- **Source**: Provided dataset (assumed to be a modified credit card dataset)
- **Size**: Contains transaction records with labeled outputs indicating fraud or not.
- **Note**: Features may be anonymized or encoded for confidentiality.

---

 Objectives

- Detect fraudulent credit card transactions.
- Handle data imbalance in a binary classification setting.
- Evaluate model performance using metrics beyond simple accuracy.
- Optionally deploy a simple prediction interface.

---

 Features

- Data cleaning & preprocessing
- Visual EDA (class distribution, correlation, outlier analysis)
- Model training (Logistic Regression, Random Forest, etc.)
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC
- Optional deployment using Flask or Streamlit

---

 Tech Stack

| Tool              | Description                     |
|-------------------|---------------------------------|
| Python            | Programming Language            |
| Pandas, NumPy     | Data manipulation               |
| Matplotlib, Seaborn | Visualization                 |
| Scikit-learn      | Machine Learning models         |
| Flask / Streamlit | (Optional) Model deployment     |
| Jupyter Notebook  | EDA and experimentation         |

---

## 📈 Model Performance

- **Best Model**: Random Forest Classifier
- **Metrics Used**: Precision, Recall, F1-score, ROC-AUC
- Special care taken to avoid overfitting and address class imbalance.

How to Run
Step 1: Clone the repository
git clone https://github.com/your-username/credit-card-fraud-detection.git

Step 2: Install dependencies
pip install -r requirements.txt

Step 3: Run the Jupyter Notebook
jupyter notebook

 (Optional) To run Flask/Streamlit app
python app.py

