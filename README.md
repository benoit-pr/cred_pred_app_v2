README

This is a streamlit app that produces a dashboard indicating a credit score.

The input is a .json file, with specific fields. Lots of example in test_data folder. 
If info is missing, the app is robust to NaNs. Note that prediction won't be as accurate.

The prediction is produced via a pretrained xgboost classifier model.

The dashboard is interactive. It shows the key information of a customer, the default probability, and whether or not the credit is given. 
It also shows the main factors contributing to decision, based on Shapley values.

It is possible to change the information to update the prediction.

To make a prediction, the model uses historical banking data, available in folder hist_data.