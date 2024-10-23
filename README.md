# Loan Data Preprocessing for Credit Risk Model

## Project Overview
This project focuses on preparing loan data from a U.S.-based bank for a credit risk model. The dataset includes loan amounts, interest rates, installment values, and other financial variables. The data has been preprocessed to convert monetary values from USD to EUR, handle missing values, and prepare categorical variables for modeling.

## Key Features
- **Currency Conversion**: Converted all monetary values from USD to EUR using a static exchange rate.
- **Missing Data Handling**: Missing values were replaced using statistical measures like minimum and maximum values, depending on the variable.
- **Data Encoding**: Categorical variables were transformed into numeric representations suitable for modeling.
- **Final Dataset**: The processed dataset has been stored in a CSV file for further analysis.

## Requirements and Guidelines
The preprocessing requirements and guidelines, including detailed variable descriptions, transformations, and final variable formats, are documented in the `loan-data-dictionary.xlsx` file. This file provides an overview of the data transformations applied and the final structure of the dataset.

## Files
- **A-Loan-Data-Example-with-NumPy-Template.ipynb**: The main notebook for data preprocessing.
- **loan-data-dictionary.xlsx**: Documentation of the original variables, applied transformations, and final processed variables.
- **loan-data-preprocessed.csv**: The output file containing the cleaned and processed dataset.
- **loan-data.xlsx**: The original, uncleaned input dataset containing raw loan data.
- **EUR-USD.xlsx**: The exchange rate file providing the USD to EUR conversion rates for the relevant time period.
