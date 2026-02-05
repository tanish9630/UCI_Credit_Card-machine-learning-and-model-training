# UCI Credit Card Default Prediction

This project applies machine learning techniques to predict credit card defaults using the UCI Credit Card dataset.

## Dataset

The dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

### Features
- **Limit Balance**: Amount of given credit.
- **Demographics**: Sex, Education, Marriage, Age.
- **Repayment Status**: History of past payment (April to September 2005).
- **Bill Amount**: Amount of bill statement.
- **Previous Payment**: Amount of previous payment.
- **Target**: Default payment (1=yes, 0=no).

## Project Workflow

1.  **Data Loading & Exploration**: Loaded the dataset and examined shape, info, and summary statistics.
2.  **Data Cleaning**: Checked for missing values and duplicates.
3.  **Preprocessing**:
    -   Renamed target column to 'default'.
    -   Standardized/Normalized numerical features (Limit Balance, Age, Bill Amounts, Pay Amounts).
    -   Split data into training (80%) and testing (20%) sets.
4.  **Modeling**:
    -   **Logistic Regression**: Implemented and evaluated.
    -   **K-Nearest Neighbors (KNN)**: Initial implementation (work in progress).

## Model Performance

### Logistic Regression
-   **Accuracy**: ~81%
-   **Precision (Class 0 - Non-Default)**: 0.82
-   **Recall (Class 0 - Non-Default)**: 0.97
-   **ROC AUC Score**: ~0.70

## Requirements

-   Python 3.x
-   pandas
-   numpy
-   scikit-learn
-   matplotlib
-   seaborn

## Usage

1.  Clone the repository.
2.  Install dependencies.
3.  Run the notebook `UCI_Credit_Card.ipynb`.
