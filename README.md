# Credit-Card-Fraud-Detection-API

This project trains a Random Forest Classifier on the credit card fraud dataset and deploys it as an API using FastAPI & ngrok in Google Colab.

🛠 Features

✅ Train a Random Forest Model for fraud detection

✅ Deploy FastAPI Server to serve predictions

✅ Expose API via ngrok for public access

✅ Test API with real transaction data

📂 Dataset

🚀 Source: creditcard.csv

🚀 Target Variable: Class (0 = Legit, 1 = Fraud)

🚀 Features: V1–V28, Amount

🔧 Setup & Run

1️⃣ Upload creditcard.csv to /content/ in Google Colab

2️⃣ Install dependencies

3️⃣ Run the notebook to train the model & start the FastAPI server

4️⃣ Get the ngrok public URL and test the API

📡 API Endpoints

1️⃣ GET / → Health check

2️⃣ POST /predict → Predict fraud

📌 Tech Stack

🔹 Python, FastAPI, Scikit-Learn, Joblib, ngrok
