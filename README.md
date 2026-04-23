# Fraudulent Job Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-7B4DFF?style=for-the-badge&logo=xgboost&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**End-to-end Machine Learning project** that detects fraudulent job postings with strong performance.

Live Demo → **[Streamlit Prediction App](https://github.com/ReubenDube/fraudulent-job-detection)**

## 📊 Project Highlights
- **Best Model**: XGBoost
- **ROC-AUC Score**: **0.9510**
- **Fraud Recall**: **0.72** (catches 72% of fraudulent jobs)
- Trained on **17,880** job postings (heavily imbalanced dataset — only 4.84% fraud)

## ✨ Features
- Interactive **Streamlit Web App** for real-time fraud prediction
- Advanced feature engineering (text length, salary info, etc.)
- Proper handling of class imbalance
- Clean, production-style code structure

## 🛠️ Technologies Used
- **XGBoost** — Main classifier
- **Pandas + Scikit-learn** — Data processing
- **Streamlit** — Interactive web interface
- **SQLAlchemy** — Loading data from ETL pipeline
- **Joblib** — Model persistence

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/ReubenDube/fraudulent-job-detection.git
cd fraudulent-job-detection

# 2. Activate virtual environment
venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Interactive Prediction App
streamlit run app.py


Connection to Project 1
This project builds directly on my Job Postings ETL Pipeline, demonstrating a complete Data Engineering → Machine Learning workflow.


🎯 Skills Demonstrated

End-to-end ML pipeline (EDA → Feature Engineering → Modeling → Deployment)
Handling severely imbalanced classification problems
Building user-friendly interactive applications with Streamlit
Model evaluation using business-relevant metrics (Recall, Precision, ROC-AUC)

🔮 Future Improvements

Text vectorization (TF-IDF / embeddings) on job descriptions
SHAP explainability for individual predictions
Model deployment (FastAPI + Docker)
Integration with my Job Portal website


