# Loan Approval Prediction Model
## Project Overview:
This project focuses on building and evaluating predictive models for loan approval using logistic regression. The goal is to develop a robust model that accurately predicts loan approval based on various covariates such as debt-to-income ratio, credit history, employment status, and more.

## Key Features:
* Model Building: Utilizes logistic regression to model the probability of loan approval.
* Variable Selection: Includes relevant covariates, such as debt-to-income ratio, credit history indicators, and employment-related variables.
* Polynomial Terms: Explores the use of polynomial terms to capture non-linear relationships.
* Cross-Validation: Implements k-fold cross-validation for robust model evaluation.
* Logit Scale Visualization: Visualizes the logit scale to understand relationships between predictors and log-odds of loan approval.

## Models Explored:
### Base Model:

* Logistic regression with debt-to-income ratio, employment status, and demographic indicators.
### Model 2:

* Introduces polynomial terms for selected variables.
* Explores the impact of additional features on predictive performance.
### Model 3:

* Further expands with additional covariates, including credit history and loan-related variables.
* Incorporates polynomial terms and explores higher-order relationships.
### Final Model:

* Selects the optimal features and polynomial terms through stepwise regression.
* Evaluates model performance using misclassification rates, AUROC, and optimal cutoff analysis.

### Logit Visualization:
The README includes visualizations of logit-transformed probabilities, offering insights into how predictor variables influence the log-odds of loan approval.

### Model Comparison:
Compares the final model's performance with the base model, highlighting improvements in misclassification rates and AUROC.

