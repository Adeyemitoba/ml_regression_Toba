# Final Project – Regression Analysis: Predicting Medical Insurance Charges

**Name:** Toba  
**Notebook:** [regression_Toba.ipynb](regression_Toba.ipynb)  
**Peer Review:** [peer_review.md](peer_review.md)  

---

## 📊 Project Overview

This project uses the [Medical Cost Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) to build regression models that predict individual medical insurance charges based on demographic and health-related features like:

- Age
- Body Mass Index (BMI)
- Number of Children
- Smoking Status
- Obesity (derived feature)

Techniques include:
- Base Linear Regression
- Pipelines (with Scaling and Polynomial Features)
- Evaluation using R², MAE, RMSE

---

## 🧪 Technologies Used

- Python 3.x
- Jupyter Notebook
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## 🛠 How to Run This Notebook Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/Adeyemitoba/ml_regression_Toba.git
   cd ml_regression_Toba

## Create a virtual environment:
* python -m venv venv
* source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install dependencies:
pip install -r requirements.txt

## Launch Jupyter:
jupyter notebook

## 📈 Key Findings
* Smoking status is the most significant factor affecting medical costs.

* Linear regression performs well but improves with feature scaling.

* Polynomial regression adds complexity and slightly improves predictions but may overfit.


## 📘 Dataset Source
Medical Cost Dataset – Kaggle