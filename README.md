# FraudShield

FraudShield compares a majority baseline, class-weighted logistic regression, and XGBoost for credit card fraud detection on the ULB dataset.

The project uses a stratified 60/20/20 train, validation, and test split with duplicate removal before splitting. XGBoost achieved the strongest overall balance on the test set with 0.685 precision, 0.800 recall, 0.738 F1, and 0.815 PR-AUC.

## Run
1. Download `creditcard.csv` from the Kaggle Credit Card Fraud Detection dataset.
2. Place it in the expected notebook path.
3. Run the notebook from top to bottom.

Random seed: `42`  
Decision threshold: `0.50`
