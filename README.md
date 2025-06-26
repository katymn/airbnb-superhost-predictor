# Airbnb Superhost Prediction with Logistic Regression

## Project Overview

This project showcases machine learning skills by solving a binary classification problem using logistic regression. The goal is to predict whether an Airbnb host is a "Superhost" based on listing features.

The work covers key stages of the machine learning lifecycle, including data preparation, model training, hyperparameter tuning, evaluation, feature selection, and model persistence.

---

## Contents

- **Data Loading & Preparation:**  
  Load and preprocess the Airbnb listings dataset, define the prediction label, and identify relevant features. The data is split into training and testing sets.

- **Model Training & Evaluation:**  
  Train logistic regression models with default and optimized hyperparameters (`C` value), including:  
  - Grid search for hyperparameter tuning  
  - Evaluation using precision-recall and ROC curves  
  - Calculation of area under the curve (AUC)

- **Feature Selection:**  
  Select the most important features to improve model simplicity and performance.

- **Model Persistence:**  
  Save the final trained model for future use or deployment.

---

## Getting Started

### Prerequisites

Make sure you have the following Python packages installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install them with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
---

## Files
airbnbData_train.csv: Preprocessed Airbnb listings dataset used for training and testing

host_is_superhost.pkl: Serialized trained logistic regression model

your_notebook.ipynb: Jupyter notebook containing the full workflow

---

## Usage
Load the dataset and prepare features and labels.

Train logistic regression models and evaluate using default and tuned hyperparameters.

Visualize precision-recall and ROC curves to compare models.

Perform feature selection and retrain the model with selected features.

Save the final model for later predictions.

---

## About
This project was completed as a part of a machine learning lab in accordance with Break Through Tech with Cornell University with a focus on the evaluation phase of the ML lifecycle. 
It demonstrates practical skills in model selection, tuning, evaluation, and persistence.

Feel free to explore the notebook for detailed code and explanations!

---

## Contact
If you have questions or feedback, reach out to me on @katymn.
