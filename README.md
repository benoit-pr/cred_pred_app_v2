# Credit Score Dashboard with Streamlit

## Overview

This Streamlit app provides an interactive dashboard for indicating a credit score.

## Input

- **File Type**: `.json`
- **Details**: The JSON file should include specific fields. Examples can be found in the `test_data` folder.
- **Handling Missing Data**: The app is robust to NaNs. However, note that predictions may be less accurate if information is missing.

## Model

- **Type**: Pretrained XGBoost Classifier
- **Repository**: [GitHub - credit_score](https://github.com/benoit-pr/credit_score)

## Features

- **Interactive Dashboard**:
  - Displays key customer information.
  - Shows the default probability and whether credit is granted.
  - Highlights the main factors contributing to the decision using Shapley values.

- **Dynamic Updates**:
  - Users can modify the input information to update predictions.

## Data

- **Historical Data**: The model uses historical banking data, which has been precomputed and is available in the `hist_data` folder.
