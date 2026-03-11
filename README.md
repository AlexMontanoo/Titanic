# Titanic Survival Prediction

This project uses the famous Titanic dataset from Kaggle to predict which passengers survived the disaster using Machine Learning techniques.

## Project Overview

The objective of this project is to build a machine learning model capable of predicting passenger survival based on demographic and travel information.

The project follows a complete machine learning workflow including:

- Data cleaning
- Missing value imputation
- Feature engineering
- Encoding categorical variables
- Model training
- Model evaluation

## Dataset

Dataset source: Kaggle  
Titanic - Machine Learning from Disaster

The dataset contains information about passengers such as:

- Passenger class
- Age
- Sex
- Fare
- Cabin
- Port of embarkation
- Family relationships on board

## Feature Engineering

Several new features were created to improve model performance:

- **FamilySize**: Total number of family members on board
- **IsAlone**: Indicates whether a passenger traveled alone
- **Title**: Extracted from passenger names (Mr, Mrs, Miss, etc.)
- **Deck**: Extracted from the Cabin feature

These engineered features provide additional information that improves model prediction capability.

## Models Evaluated

The following machine learning models were tested:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Best Model

The best performance was achieved using **Random Forest**, reaching an accuracy of approximately **82%** on the validation set.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

## Project Structure
