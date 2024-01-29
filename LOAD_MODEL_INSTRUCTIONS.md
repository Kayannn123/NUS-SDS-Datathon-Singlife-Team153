# Load Instructions for Trained Model

This document provides instructions on how to load the trained Random Forest Classifier model for predictions.

## Prerequisites

Make sure you have the following software/libraries installed:

- Python (version X.X.X)
- scikit-learn (version X.X.X)
- joblib (version X.X.X)

## Load the Trained Model
1. **Download the Model File:**
   - Download the saved Random Forest Classifier model file (`random_forest_model.joblib`) from https://drive.google.com/file/d/1BenZdEPishoAN0JJhMFG1T05OVSCJtEY/view?usp=sharing.

2. **Install Required Dependencies:**
   - Open a terminal or command prompt.
   - Install the required Python libraries if not already installed:
     ```bash
     pip install scikit-learn joblib
     ```

3. **Load the Model in Python:**
   - Use the following code to load the model in a Python script or Jupyter notebook:

     ```python
     import joblib

     # Load the saved model
     loaded_rf_model = joblib.load('random_forest_model.joblib')

     # Now you can use loaded_rf_model for predictions on new data
     # new_data_predictions = loaded_rf_model.predict(new_data)
     ```

4. **Make Predictions:**
   - Use the loaded model to make predictions on new data.
   - Example:

     ```python
     # Assuming you have new data stored in 'new_data'
     new_data_predictions = loaded_rf_model.predict(new_data)
     ```

5. **Additional Information:**
   - The trained model was originally created using scikit-learn's RandomForestClassifier with 100 estimators.


