# Fraudulent Job Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-7B4DFF?style=for-the-badge&logo=xgboost&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**End-to-end Machine Learning project** that detects fraudulent job postings with **high accuracy**.

Live Demo: Streamlit Prediction App

## 📊 Key Results
- **Best Model**: XGBoost
- **ROC-AUC Score**: 0.9510
- **Fraud Recall**: 0.72 (catches 72% of actual fraudulent jobs)
- Trained on 17,880 job postings (4.84% fraud rate)

## ✨ Features
- Interactive **Streamlit Web App** for real-time fraud prediction
- Handles severe class imbalance
- Feature engineering from job metadata and text length
- Clear model explainability (feature importance)

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/ReubenDube/fraudulent-job-detection.git
cd fraudulent-job-detection

# 2. Activate virtual environment
venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the prediction app
streamlit run app.py


🛠️ Technologies Used

XGBoost – Main model
Pandas + Scikit-learn – Data processing
Streamlit – Interactive web interface
SQLAlchemy – Data loading from ETL pipeline

🔗 Connection to Project 1
This project builds directly on my Job Postings ETL Pipeline, showing a complete Data Engineering → Machine Learning workflow.

🎯 Skills Demonstrated

End-to-end ML pipeline development
Handling imbalanced classification problems
Feature engineering and model interpretation
Building interactive data applications with Streamlit
Reproducible and well-documented projects