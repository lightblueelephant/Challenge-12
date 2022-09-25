# Challenge-12

Credit Risk Analysis Report

The file “MC_credit_risk_resampling.ipynb” contains code used to build two logistic regression models and determine their effectiveness at identifying low-risk vs high-risk loans for potential borrowers. These models were built on loan information from existing accounts in the “lending_data.csv” file. Using the “value_counts” function in python it is possible to see that there are 75036 unique values for healthy loans and 2500 unique values for high risk loans in the first model and 56271 unique values for each in the random over-sampled model. The stages for machine learning for these models included model, fit, predict. The model was built, fit to the existing data, and then used to predict future outcomes. Methods used included logistic Regression and resampling. Logistic Regression is designed to predict discrete outcomes—is the loan high or low risk? Random oversampling is useful when not enough data is present, however it can cause “overfitting” which makes it a potentially risky tool. 

Results for Model 1 and Model 2
	Balanced_accuracy_score
•	Used for imbalanced data 
•	Mathematical mean of sensitivity and specificity 
•	Regular model value: 0.95
•	Random oversampled model value: 0.99
•	Both values show model is highly accurate
Precision Scores
•	Accuracy of positive predictions (what percent of positive predictions was correct?)
•	Regular model:
o	Low risk: 100%, high risk: 85%
•	Random oversampled model:
o	Low risk: 100%, high risk: 84%
Recall Scores
•	Fraction of positives correctly ID’d
•	Regular Model:
o	Low risk: 99%, high risk: 91%
•	Random oversampled model:
o	Low risk: 99%, high risk 99%

Summary
It appears that the random oversampling model is slightly better than the regular model as evidenced by its recall and balanced_accuracy scores. However, both models are still useful and it is recommended that both be used. Ultimately, it is more important to be able to predict if a loan is high risk rather than low risk, meaning it is more important to be able to predict the “1s”. 
