# Churn
# Customer Churn Prediction Model

This repository contains a machine learning model for predicting customer churn. The model takes customer-related features as input and predicts whether the customer is likely to churn ("Churn") or stay ("No Churn").

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Contributing](#contributing)
- [License](#license)

## About the Project

Customer churn prediction is essential for businesses to retain customers and increase revenue. This project uses machine learning to predict customer churn based on a variety of customer characteristics. It utilizes a logistic regression model trained on a labeled dataset, where features have been preprocessed and encoded to improve accuracy.

The project also includes a user-friendly web interface created with Gradio, making it easy for users to interact with the model without needing programming experience.

## Features

- **Churn Prediction**: Predicts whether a customer is likely to churn or not.
- **Preprocessing**: Encodes categorical features, one-hot encodes multi-category features, and applies min-max scaling on numerical features.
- **Web Interface**: Uses Gradio for a simple and interactive user interface.

## Installation

Follow these steps to install the required dependencies and set up the project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
Install dependencies: This project requires Python 3.x and the following Python libraries:

pandas
numpy
joblib
gradio
Ensure Model Files are in Place: Place the following model and encoder files in the model/ directory:

label_encoders.pkl
one_hot_encoder.pkl
min_max_scaler.pkl
logistic_regression_model.pkl
label_encoder_target.pkl
Usage
To start the prediction app:

Run the app.py script:

bash
Copy code
python app.py
Once the script is running, a link will appear in the terminal (something like http://127.0.0.1:7860/). Open it in a web browser to access the Gradio interface.

Fill in the customer data fields in the interface, and click the "Submit" button. The model will predict whether the customer is likely to churn or not.

Model Details
Model: Logistic Regression
Preprocessing:
Label encoding for binary categorical features
One-hot encoding for multi-class categorical features
Min-max scaling for numerical features
Libraries: joblib for saving and loading the model, Gradio for building the interactive interface
Contributing
Contributions are welcome! If you'd like to improve this project, please follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature/YourFeature.
Commit your changes: git commit -m 'Add YourFeature'.
Push to the branch: git push origin feature/YourFeature.
Open a pull request.
License
Distributed under the MIT License. See LICENSE for more information
https://huggingface.co/spaces/Mostafa999/Mostafa-fathi
