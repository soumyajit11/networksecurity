### Net security projects for phising data

# CyberNet: ML-powered Network Intrusion Detection Pipeline 🚀

A complete Machine Learning pipeline to perform network security threat detection — from data ingestion to model deployment, built with FastAPI, MLflow, and Python.

---

## 🔗 Demo Video

👉 [Watch Full Demo on YouTube](https://youtu.be/Tvo394MOjpA)

---

## 🧠 Problem Statement

The goal of this project is to automate the process of detecting network anomalies and cyber threats using machine learning. The system is capable of ingesting raw data, validating it, transforming features, training ML models, and serving predictions via a REST API.

---

## ⚙️ Tech Stack

- **Python 3.10**
- **FastAPI** (Backend API)
- **MLflow** (Experiment Tracking)
- **Scikit-learn** (ML Model Training)
- **Pandas & NumPy** (Data Processing)
- **Uvicorn** (ASGI Server)
- **Swagger/OpenAPI** (API Documentation)

---


---

## 🔬 ML Pipeline Stages

1️⃣ **Data Ingestion**  
- Load raw CSV data into feature store
- Split into train-test datasets

2️⃣ **Data Validation**  
- Check schema consistency
- Separate valid & invalid datasets
- Generate data drift reports

3️⃣ **Data Transformation**  
- Handle missing values, scaling
- Transform categorical data
- Save transformed datasets as `.npy`

4️⃣ **Model Training**  
- Train ML model (e.g., RandomForest, XGBoost)
- Evaluate model accuracy
- Save trained model artifacts

5️⃣ **Deployment**  
- Expose `/predict` API via FastAPI
- Upload CSV files to get predictions

---

## 🚀 Running the Project

### 1️⃣ Clone Repository

```bash
git clone https://github.com/soumyajit11/networksecurity.git
cd networksecurity


### 2️⃣ Create Virtual Environment

```bash
conda create -n venv python=3.10
conda activate venv/


### 3️⃣ Install Requirements

```bash
pip install -r requirements.txt


### 4️⃣ Start FastAPI Server
```bash
uvicorn app:app --reload

The Swagger UI will be available at:
👉 http://127.0.0.1:8000/docs

🗄️ MLflow Experiment Tracking
MLflow is integrated to log metrics, artifacts, and models.

Easy to compare multiple experiments.

🔮 Future Improvements
Dockerize the complete pipeline

Add CI/CD pipeline (GitHub Actions)

Use MongoDB for real-time data ingestion

Integrate authentication & role-based access control

Host API on cloud platform (AWS/GCP/Azure)

🏅 Author
Soumyajit Banik
B.Tech | Full Stack & AIML Engineer | ML Enthusiast


## 📚 Disclaimer

This project was developed as part of my learning journey while completing the following Udemy course:

> **Course**: Complete Machine Learning & NLP Bootcamp — MLOps Deployment  
> [Course Link](https://www.udemy.com/course/complete-machine-learning-nlp-bootcamp-mlops-deployment/?couponCode=KEEPLEARNING)

The repository reflects my hands-on practice and understanding of building a full ML pipeline with deployment.


