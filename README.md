# Medical-Cost-prediction
## Project Overview

This project focuses on predicting individual medical insurance charges using demographic and lifestyle information. The goal is to evaluate the effectiveness of machine learning models for cost prediction on structured healthcare data using Python.

## Dataset

The dataset originates from the public-domain insurance cost data associated with *Machine Learning with R* by Brett Lantz. The data were cleaned and reformatted to ensure consistency and usability for predictive modeling in Python.

### Features
- **age**: Age of the primary beneficiary  
- **sex**: Gender of the insurance contractor (female, male)  
- **bmi**: Body Mass Index (kg/m²)  
- **children**: Number of dependents covered by the insurance  
- **smoker**: Smoking status  
- **region**: Residential area in the US (northeast, southeast, southwest, northwest)  
- **charges**: Medical costs billed by health insurance (target variable)

## Methodology

- Data preprocessing and encoding of categorical variables  
- Exploratory data analysis (EDA)  
- Feature engineering  
- Training and evaluation of regression models for cost prediction  
- Performance assessment using appropriate regression metrics  

## Tools and Libraries

- Python  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  

## Objective

To assess how well machine learning models can predict medical insurance charges based on demographic and lifestyle factors, and to identify key contributors to cost variability.

## Inspiration

Can healthcare costs be accurately predicted from tabular demographic data using machine learning?
## Code

The full implementation is available in the Jupyter notebook:
- `notebooks/medical_cost_prediction.ipynb`

