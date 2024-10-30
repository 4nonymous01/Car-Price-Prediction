# Car-Price-Prediction


Project Overview

This project aims to predict the selling price of used cars based on user inputs such as car brand, year of manufacture, kilometers driven, fuel type, seller type, transmission type, and owner type. The prediction model leverages both a machine learning pipeline and a Flask web application to offer user-friendly interaction and predictions based on user inputs.



Features and Workflow

1. User Input Collection**: Through the `index.html` form, users select a car’s brand, year, kilometers driven, fuel type, seller type, transmission type, and owner type.

2. Data Processing**:

   - `model_training.py` loads and processes data to train the model. Data includes car company, year, kilometers driven, and encoded categories for fuel, seller, transmission, and ownership types.

   - After data encoding and scaling, features and labels are split, and the model is trained.

4. Prediction and Multiplier Logic:

   - In `app.py`, user inputs are scaled and fed to the trained model.

   - Predicted prices are adjusted based on a brand-specific multiplier to account for brand influence.

6. Error Handling and Display:

   - The app checks for missing fields, ensuring all necessary inputs are provided.

    - JavaScript dynamically displays the prediction result on the web page.

Technologies Used

- Flask: For handling server-side functionality, routing, and rendering HTML templates.

- TensorFlow and Keras: To build and train the neural network model that predicts car prices.

- Joblib: For saving and loading the trained scaler.

- HTML, CSS, JavaScript: Front-end components for form handling, styling, and displaying results.

- Pandas: For data preprocessing.

- Scikit-Learn: For data encoding, scaling, and model evaluation.


OUTPUT :

![image](https://github.com/user-attachments/assets/6b2a6c9e-8ebf-4259-a741-4c2651b5c50f)

