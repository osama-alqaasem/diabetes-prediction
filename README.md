# Diabetes Prediction

Machine Learning project for predicting diabetes based on clinical and health-related features.

## Project Components

- `diabetes_model.joblib` — Trained machine learning model.
- `scaler.joblib` — Feature scaling object used during preprocessing.
- `feature_order.joblib` — Stores the expected feature order.
- `app.ipynb` — Notebook for prediction and application usage.
- `train_and_save_model.ipynb` — Notebook for training and saving the model.

## Workflow

The project follows these steps:

1. Load the diabetes dataset.
2. Preprocess the input features.
3. Scale the features using the saved scaler.
4. Arrange the features according to the required order.
5. Pass the processed data to the trained model.
6. Generate the diabetes prediction.

## Technologies

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy
- Joblib

## Model Files

The trained model and preprocessing objects are stored using Joblib so they can be loaded later without retraining the model.

## Disclaimer

This project is for educational and research purposes only and should not be used as a substitute for professional medical diagnosis.
