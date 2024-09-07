

# Disease Predict Web App
url - https://disease-predict-web-app.streamlit.app/

This repository contains the code and models for a web application that predicts multiple diseases, including:

- Diabetes
- Heart Disease
- Breast Cancer
- Parkinson’s Disease

The models were trained using machine learning algorithms and deployed using Streamlit for real-time prediction.

## Features

- **Diabetes Prediction:** Based on features like pregnancies, glucose levels, blood pressure, etc.
- **Heart Disease Prediction:** Using medical data such as cholesterol levels, resting ECG results, etc.
- **Breast Cancer Detection:** Predicts whether breast cancer is malignant or benign using tumor data.
- **Parkinson’s Disease Prediction:** Based on vocal measurements and other medical attributes.

## File Structure

- `multiple_disease_pred.py`: Main application script.
- `diabetes_model.sav`: Trained model for diabetes prediction.
- `heart_disease_model.sav`: Trained model for heart disease prediction.
- `breastcancer_model.sav`: Trained model for breast cancer prediction.
- `parkinsons_model.sav`: Trained model for Parkinson’s disease prediction.
- `requirements.txt`: Python packages required to run the application.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/vars7x/disease-predict-web-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd disease-predict-web-app
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run multiple_disease_pred.py
   ```

5. Open the app in your browser at `http://localhost:8501`.

## Models

The models were trained using various machine learning algorithms such as Logistic Regression, SVM, and others, with an accuracy of around 92% for multiple disease predictions.

