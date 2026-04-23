# Fraudulent Job Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-7B4DFF?style=for-the-badge&logo=xgboost&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**End-to-end Machine Learning project** to detect fraudulent job postings.

Built on top of my [Job Postings ETL Pipeline](../job-postings-etl-pipeline).

## 📊 Project Highlights
- **Best Model**: XGBoost
- **ROC-AUC Score**: 0.9510
- **Fraud Recall**: 0.72 (catches 72% of fraudulent jobs)
- Handled severe class imbalance (only 4.84% fraudulent cases)
- Feature engineering from raw job text and metadata

## 🛠️ Technologies
- Python, Pandas, Scikit-learn
- XGBoost Classifier
- SQLAlchemy (data loading)
- Matplotlib / Seaborn (visualization)
- Joblib (model persistence)

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/ReubenDube/fraudulent-job-detection.git
cd fraudulent-job-detection

# 2. Activate virtual environment
venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Train / Run the model
cd scripts
python improved_model_training.py


Key Results

Trained on 17,880 job postings
Strong performance on imbalanced fraud detection task
Clear feature importance analysis

🔗 Project Connection
This project builds directly on my Job Postings ETL Pipeline, demonstrating a complete Data Engineering → Machine Learning workflow.

🎯 Skills Demonstrated

End-to-end ML pipeline development
Handling class imbalance in fraud detection
Feature engineering and importance analysis
Model evaluation using proper metrics (ROC-AUC, Precision, Recall)
Reproducible project structure

🔮 Future Work

Text vectorization (TF-IDF / embeddings) on job description/title
Model deployment as a Streamlit web app
API integration with Job Portal


Part of my Data Scientist / ML Engineer Portfolio