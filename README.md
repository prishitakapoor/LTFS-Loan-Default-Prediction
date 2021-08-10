# LTFS-Loan-Default-Prediction-(Vehicle) 
Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate the determinants of vehicle loan default.

# Following Information regarding the loan and loanee are provided in the datasets:

1. Loanee Information (Demographic data like age, income, Identity proof etc.)
2. Loan Information (Disbursal details, amount, EMI, loan to value ratio etc.)
3. Bureau data & history (Bureau score, number of active accounts, the status of other loans, credit history etc.)
4. Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified which can be further used for minimising the default rates.

# Data Description

1. train.zip contains train.csv and data_dictionary.csv.
2. train.csv contains the training data with details on loan as described in the last section
3. data_dictionary.csv contains a brief description on each variable provided in the training and test set.
4. test.csv contains details of all customers and loans for which the participants are to submit probability of default.
5. sample_submission.csv contains the submission format for the predictions against the test set. A single csv needs to be submitted as a solution.



# Evaluation Metric
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.
