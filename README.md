# Challenge-12

**Package Requirements and Versions: pip install x versions -python -pandas -pathlib -sklearn 

Purpose of Use: utilize lending_data.csv to form 2 logistic regression models to predict creditworthiness of potential borrowers
This code contains multiple parts: 

Part 1: Split Data into Training and Testing Sets
  Step 1: Read the lending_data.csv data from the Resources folder into a Pandas DataFrame
  Step 2: Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
  Step 3: Check the balance of the labels variable (y) by using the value_counts function.
  Step 4: Split the data into training and testing datasets by using train_test_split.
  
Part 2: Create a Logistic Regression Model with the Original Data
  Step 1: Fit a logistic regression model by using the training data (X_train and y_train).
  Step 2: Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
  Step 3: Evaluate the model’s performance.
  
  Part 3: Predict a Logistic Regression Model with Resampled Training Data
 Step 1:  Use the RandomOverSampler module from the imbalanced-learn library to resample the data. Be sure to confirm that the labels have an equal number of data points.
Step 2: Use the LogisticRegression classifier and the resampled data to fit the model and make predictions
Step 3: Evaluate the model's performance

File Navigation MC_credit_risk_resampling.ipynb (code explanation and notebook for building), lending_data.csv (existing lending data), Credit_Risk_Report (report recommending models with further summary and analysis)
© 2022 GitHub, Inc.
Footer navigation

