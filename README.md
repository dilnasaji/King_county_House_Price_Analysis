# King County House Price Analysis & Prediction

## Project Overview

This project analyzes residential property sales in King County, Washington, to explore the factors associated with house prices and develop regression models for price prediction. The project was completed as part of the IBM Data Analysis with Python course and has been organized as part of my data analytics portfolio.

## Objectives

- Clean and prepare housing data for analysis
- Explore relationships between property characteristics and price
- Identify important variables associated with house prices
- Develop and compare regression models
- Evaluate model performance on unseen data

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Analysis Workflow

1. Data Loading & Inspection
2. Data Cleaning & Preparation
3. Exploratory Data Analysis
4. Correlation Analysis
5. Regression Model Development
6. Train/Test Evaluation
7. Ridge Regression
8. Polynomial Feature Transformation
9. Model Comparison

## Model Results

| Model | Evaluation Data | R² |
|---|---|---:|
| Simple Linear Regression | Fitted Data | 0.493 |
| Multiple Linear Regression | Fitted Data | 0.658 |
| Polynomial Regression Pipeline | Fitted Data | 0.751 |
| Ridge Regression | Test Data | 0.648 |
| Polynomial Features + Ridge | Test Data | 0.700 |

## Key Findings

- Living area showed one of the strongest positive relationships with house price.
- Incorporating multiple property characteristics improved the fitted model compared with using living area alone.
- Polynomial transformations captured additional relationships within the housing data.
- Polynomial Features + Ridge Regression achieved an R² of approximately 0.700 on the held-out test data.
- Evaluating models on unseen data provided a better indication of model generalization.

## Key Learning

This project strengthened my understanding of how data cleaning, exploratory analysis, feature relationships, regression modeling, regularization, and model evaluation connect within an end-to-end Python data analysis workflow.

## Project Context

This project was completed as an applied project within IBM's Data Analyst course with Python coursework. The notebook has been reorganized and documented for portfolio presentation and to reflect my understanding of the analytical workflow.
