# Boston House Pricing Prediction

This project predicts housing prices in Boston using Machine Learning techniques. The model is trained on the Boston Housing dataset and deployed as a web application for real-time predictions.

---

## Project Overview

The Boston House Pricing Prediction project aims to estimate the median value of owner-occupied homes based on various housing features such as crime rate, number of rooms, property tax rate, and more.

The project follows a complete Machine Learning lifecycle:

* Data Collection
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training
* Model Evaluation
* Web Application Development
* Deployment

---

## Software and Tools Requirements

### Required Accounts

* GitHub Account
* Heroku Account (Optional for Deployment)

### Required Software

* VS Code IDE
* Git CLI
* Python 3.7+
* Anaconda or Miniconda

---

## Project Structure

```text
Boston-House-Pricing-Prediction/
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── prediction.py
│
├── templates/
│   └── home.html
│
├── static/
│
├── app.py
├── requirements.txt
├── setup.py
├── README.md
└── model.pkl
```

---

## Create a New Environment

Using Conda:

```bash
conda create -p venv python==3.7 -y
```

Activate Environment:

### Windows

```bash
conda activate venv/
```

### Linux / macOS

```bash
source activate venv/
```

---

## Install Required Packages

```bash
pip install -r requirements.txt
```

---

## GitHub Setup

Initialize Git Repository:

```bash
git init
```

Add Files:

```bash
git add .
```

Commit Changes:

```bash
git commit -m "Initial Commit"
```

Create Main Branch:

```bash
git branch -M main
```

Connect GitHub Repository:

```bash
git remote add origin https://github.com/yourusername/Boston-House-Pricing-Prediction.git
```

Push Code:

```bash
git push -u origin main
```

---

## Run Application Locally

Start Flask Application:

```bash
python app.py
```

Application will run at:

```text
http://127.0.0.1:5000
```

---

## Machine Learning Workflow

### Step 1: Data Collection

Load Boston Housing Dataset.

### Step 2: Data Preprocessing

* Handle missing values
* Remove duplicates
* Scale features

### Step 3: Exploratory Data Analysis

* Correlation Analysis
* Feature Distribution
* Outlier Detection

### Step 4: Model Training

Algorithms Used:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

### Step 5: Model Evaluation

Evaluation Metrics:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

### Step 6: Model Deployment

Deploy trained model using:

* Flask
* Heroku

---

## Deployment on Heroku

### Login to Heroku

```bash
heroku login
```

### Create Application

```bash
heroku create boston-house-price-prediction
```

### Deploy Application

```bash
git push heroku main
```

Open Application:

```bash
heroku open
```

---

## Requirements

Example requirements.txt

```text
Flask
numpy
pandas
scikit-learn
matplotlib
seaborn
xgboost
gunicorn
```

Install all packages:

```bash
pip install -r requirements.txt
```

---

## Example Prediction Inputs

| Feature | Description                    |
| ------- | ------------------------------ |
| CRIM    | Crime Rate                     |
| ZN      | Residential Land Zoned         |
| INDUS   | Non-retail Business Acres      |
| CHAS    | Charles River Dummy Variable   |
| NOX     | Nitric Oxides Concentration    |
| RM      | Average Number of Rooms        |
| AGE     | Age of Property                |
| DIS     | Distance to Employment Centers |
| TAX     | Property Tax Rate              |
| PTRATIO | Pupil-Teacher Ratio            |

---

## Results

The trained model predicts house prices with high accuracy and provides users with real-time estimates through a web interface.

---

## Future Improvements

* Docker Deployment
* AWS Deployment
* CI/CD Pipeline
* Advanced Feature Engineering
* Model Monitoring
* User Authentication

