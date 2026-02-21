
# 💰 Webfala Loan Eligibility Predictor

An end-to-end Machine Learning web application that predicts whether a loan applicant is eligible for a loan based on personal and financial information.

Built using:
- Python
- Scikit-learn
- Streamlit
- Joblib

## 🚀 Project Overview

This project uses a trained Machine Learning model (Decision Tree Classifier) to predict loan eligibility.

Users can input details such as:
- Gender
- Marital status
- Income
- Loan amount
- Credit history
- Property area

The model returns:
- Loan eligibility prediction
- Confidence score
Link to demo https://webfalaloanpredictor-ctx9oa7nvmgmqpupsmayfs.streamlit.app/
## 🧠 Machine Learning Approach

- Algorithm: Decision Tree Classifier
- Data preprocessing: Label encoding
- Model serialization: Joblib
- Evaluation: Accuracy-based classification

The model was trained on structured loan application data and saved for deployment.

## 🏗 Project Structure
webfala_loan_predictor/
│
├── app.py
├── predictor.py
├── requirements.txt
├── model/
│ └── dt_clf.joblib
└── README.md


---

## 📦 Requirements

- streamlit
- pandas
- scikit-learn
- joblib
- numpy

---

## 🎯 Features

- User-friendly web interface
- Real-time prediction
- Confidence score display
- Clean modular code structure
- Ready for deployment

---

## 🌍 Deployment

This project can be deployed using:
- Streamlit Cloud
- Render
- HuggingFace Spaces

---

## 👩🏽‍💻 Author

**Patience Mamman**

Data Science & Machine Learning Enthusiast


## 📌 Future Improvements

- Add model performance metrics
- Use Pipeline for better preprocessing
- Improve model accuracy
- Add feature importance visualization
- Deploy live version with public link

## 📜 License

This project is for educational purposes.

