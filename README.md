# Diabetes Prediction

![Python](https://img.shields.io/badge/Python-3.7%20%7C%203.8-blue)

This project analyzes patient data to predict if a person is a diabetic patient or not. It utilizes various parameters from the dataset, including age, hypertension status, smoking history, blood glucose level, and body mass index (BMI).

## Table of Contents
- [Background](#background)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Evaluation](#evaluation)
- [Contributing](#contributing)

## Background

The goal of this project is to develop a predictive model for diabetes based on patient data. By analyzing various parameters, such as age, hypertension, smoking history, blood glucose level, and BMI, we aim to build a machine learning model that can accurately predict whether a patient has diabetes or not.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/riabhatnagar0610/Diabetes-Prediction.git
   ```

2. Change to the project directory:

   ```shell
   cd Diabetes-Prediction
   ```

3. Install the required dependencies:

   ```shell
   pip install -r requirements.txt
   ```

## Usage

To use this project, follow these steps:

1. Prepare your dataset: Ensure your dataset is cleaned and contains the necessary parameters.

2. Train the model: Run the `diabetes_prediction.py` script to train the machine learning model using your dataset.

   ```shell
   python diabetes_prediction.py
   ```

3. Predict diabetes: After training the model, you can use it to predict if a patient has diabetes or not.

## Dataset

The dataset used for this project should contain the following parameters:

- `age`: The age of the patient (numeric).
- `hypertension`: Whether the patient has hypertension or not (0 = No, 1 = Yes).
- `smoking`: Smoking history of the patient (categorical).
- `blood_glucose`: Blood glucose level of the patient (numeric).
- `bmi`: Body mass index (BMI) of the patient (numeric).
- `diabetes`: The target variable indicating whether the patient has diabetes or not (0 = No, 1 = Yes).

## Evaluation
To evaluate the performance of the machine learning models, the project utilizes various metrics such as accuracy, precision, recall, and F1 score. These metrics provide insights into the model's ability to correctly predict diabetic patient.
The highest accuracy received is 96.8% from Random Forest Classifier.

## Contributing

Contributions are welcome! If you have any suggestions or find any issues, please feel free to open an issue or submit a pull request.
