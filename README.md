**Name:** Ramoju Gnana Deepika

**Company:** CODETECH IT solutions

**Id:** CT6WSFC

**Domain:** Data Science

**Duration:** February 25th to April 10th, 2025

**Mentor:** N.Santhosh

### Project Overview: Iris Flower Classification with Flask API
## Objective:
To build a machine learning model that predicts the species of an iris flower based on the flower's physical features, and deploy this model as a Flask API so users can make predictions via a web interface or API call.

## Dataset:
--**Source:** Built-in Iris dataset from scikit-learn
--**Features:**
Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)
--**Target:** Flower Species
0 → Setosa
1 → Versicolor
2 → Virginica

##Model Used:
--**Algorithm:** Logistic Regression
--**Libraries:** scikit-learn, pandas, joblib
--**Performance:** Suitable for small, multi-class classification tasks like this one

## Tech Stack:
Python for scripting
Flask for building the API
Joblib for saving and loading the trained ML model
Postman / Curl for testing the API
Optional deployment platforms: Render, Railway, or Heroku

## Workflow
--**Load & Prepare Data**
Load iris dataset using sklearn.datasets.load_iris()

--**Train Model**
Split data → Train Logistic Regression Model → Save with joblib

--**Build Flask API**
Create a Flask server with a /predict endpoint
Accept JSON input and return prediction (species of flower)

--**Test API Locally**
Use Postman or curl to test with real values

--**Deploy API (Optional)**
Push to GitHub
Deploy on Render with Procfile and requirements.txt

## Input Example
{
  "sepal_length": 5.1,
  "sepal_width": 3.5,
  "petal_length": 1.4,
  "petal_width": 0.2
}

## Output Example
{
  "prediction": 0,
  "flower_type": "Setosa"
}

## Outcome
You now have a working API that can classify iris flowers based on user input!
The project demonstrates the full Data Science pipeline:
        Data Collection → Preprocessing → Model Training → Model Deployment


