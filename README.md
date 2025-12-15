
# Fraud Detection Project

## Overview

Fraud detection is a critical challenge in modern digital payment systems, where high transaction volumes and multiple access channels create opportunities for fraudulent activity to occur alongside legitimate behavior. 

This project focuses on detecting fraudulent transactions using machine learning. 

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/aderemi1224/fraud_detection_app.git
   cd fraud_detection_project
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Running EDA

Open `Fraud_EDA` in Jupyter or VSCode.

## Running Model Training

Open `Fraud_Detection`.

## Running Demo

```bash
streamlit run demo/app.py
```

## Expected Outputs

* EDA report: `EDA_report.ipynb`
* Trained model: `rf_fraud_model.pkl`
* Interactive demo: Streamlit interface for predicting fraud.
  """

---

# requirements.txt:


pandas

numpy

scikit-learn

matplotlib

seaborn

streamlit

joblib


---

# Demo Instructions

1. Ensure you have installed all requirements.
2. Run the demo using Streamlit:

   ```bash
   streamlit run app.py
   ```
3. Use the sample data to test the fraud detection model.
4. The app will display predictions and probability scores.
   """
