# Spam Classification Project

## Overview
This project demonstrates a machine learning approach to classify emails as spam or not spam using two different models:
- **Logistic Regression**
- **Random Forest Classifier**

The dataset consists of word and character frequency features extracted from emails, and the target label is binary: 1 for spam, 0 for non-spam.

## Project Structure
- **data**: The spam dataset trains and evaluates the models.
- **models**: Two models are used in the project:
  - Logistic Regression
  - Random Forest Classifier
- **evaluation**: Both models are evaluated based on accuracy.

## Steps Performed
1. **Data Loading and Preprocessing**:
    - Loaded the dataset and separated it into features (`X`) and the target label (`y`).
    - Split the data into training and testing sets.
    - Scaled the features using `StandardScaler` to standardize the data for the models.
    
2. **Model Training**:
    - Trained a **Logistic Regression** model and calculated its accuracy.
    - Trained a **Random Forest Classifier** model and calculated its accuracy.
    
3. **Model Comparison**:
    - Both models were evaluated on the test data, and their performances were compared based on accuracy scores.

## Results
- **Logistic Regression Model Accuracy**: (.9197)
- **Random Forest Classifier Model Accuracy**: (.9555)

The Random Forest Classifier outperformed the Logistic Regression model, confirming the hypothesis that an ensemble model like Random Forest handles complex, non-linear data better.

## Dependencies
To run this project, ensure you have the following Python libraries installed:

```bash
pip install pandas scikit-learn
