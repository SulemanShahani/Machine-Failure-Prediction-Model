# Machine Failure Prediction Model

This repository contains a machine learning model to predict machine failures based on various parameters.

## Project Overview

The goal of this project is to develop a machine learning model that predicts machine failures based on various operational parameters. The model uses historical data to classify machines as either operating normally or likely to fail, helping in preemptive maintenance and reducing downtime.

## Dataset

The dataset used for this project includes the following columns:

- `Air temperature [K]`: Temperature of the air in Kelvin.
- `Process temperature [K]`: Temperature of the process in Kelvin.
- `Rotational speed [rpm]`: Rotational speed of the machine in revolutions per minute.
- `Torque [Nm]`: Torque exerted by the machine in Newton-meters.
- `Tool wear [min]`: Accumulated tool wear in minutes.
- `Machine failure`: Binary variable indicating whether a machine failure occurred (`1` for failure, `0` for no failure).

## Methodology

### Data Preprocessing

- **Handling Missing Data**: Missing values were imputed using the mean/median of the respective columns.
- **Feature Scaling**: Numerical features were scaled using standardization to ensure all features contribute equally to the model.

### Model Selection

Three models were evaluated for this project:

1. **Decision Tree Classifier**:
   - Used for its interpretability and ability to handle non-linear relationships.

2. **Logistic Regression**:
   - A simple yet effective model for binary classification tasks.

3. **Random Forest Classifier**:
   - Chosen for its robustness and ability to handle complex datasets.

### Model Training and Evaluation

- **Decision Tree Classifier**:
  - Trained the model and evaluated its performance.

- **Logistic Regression**:
  - Trained the model and evaluated its performance.

- **Random Forest Classifier**:
  - Trained the model and evaluated its performance.

### Model Interpretation

- **Feature Importance (Random Forest)**:
  - Identified important features for predicting machine failures.

- **Visualizing Decision Trees**:
  - Visualized decision trees to understand model decisions.

### Results

- **Model Performance**:
  - Decision Tree Classifier Accuracy: XX%
  - Logistic Regression Accuracy: XX%
  - Random Forest Classifier Accuracy: XX%

- **Feature Importance**:
  - `Tool wear [min]` was found to be the most important feature in predicting machine failures.

### Usage

#### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/machine-failure-prediction.git
   cd machine-failure-prediction
   



