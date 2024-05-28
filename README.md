# Kaggle Competition Prediction App

This Streamlit web application enables users to train machine learning models and make predictions for Kaggle competitions. Users can upload their training and test datasets, select a machine learning model, and evaluate the model's performance.

## Features
- Upload `train.csv`, `test.csv`, and `sample_submission.csv` files.
- Choose from multiple machine learning models: Logistic Regression, Random Forest, SVM, or Hist Gradient Boosting.
- Train the selected model on the training data.
- Evaluate the model's performance using accuracy, precision, recall, and F1 score.
- Make predictions on the test data and download the predicted output as a CSV file.

## How to Use
1. **Upload Data Files**:
   - Upload your `train.csv`, `test.csv`, and `sample_submission.csv` files using the respective file uploaders.
   - Specify the target column name and ID column name.

2. **Choose Model**:
   - Select a machine learning model from the dropdown menu.

3. **Train Model**:
   - Click on the "Train Model" button to train the selected model on the training data.

4. **Evaluate Model**:
   - View the evaluation metrics (accuracy, precision, recall, and F1 score) for the trained model.

5. **Make Predictions**:
   - The app makes predictions on the test data using the trained model.
   - View the predicted output in a table format.

6. **Download Predictions**:
   - Download the predicted output as a CSV file using the "Download Predictions as CSV" button.

## Requirements
- Python 3.6 or later
- Streamlit
- pandas
- scikit-learn

## How to Run
1. Install the required dependencies using `pip install -r requirements.txt`.
2. Run the app with `streamlit run app.py`.

## Contributors
- Tasswar Abbas - [@abbas829](https://github.com/abbas829)

