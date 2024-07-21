# Arkmind AI Engineer Technical Assessment 1
## Task Description
Your task is to train a classification model using a dataset containing various features related to loan data. The goal is to classify the status of the application (APPROVE/REJECT) based on the provided features.

## Dataset
The dataset (`data.csv`) contains columns including applicant personal information and loan information.

Column description:
- loanApplied - Loan amount which applied by applicant
- financeAmount - Approved loan amount
- ela - Maximum loan amount which the applicant is eligible to loan based on his/her financial capability
- netSalary - Applicant net salary
- loanTenure - Loan tenure
- interestRate - Loan interest rate in percentage
- applicationStatus - final status decided by management team (APPROVED/REJECTED)

The target for this dataset is applicationStatus.

## Requirements
- Use any programming language or framework of your choice for model training.
- Preprocess the data and split the dataset into training and testing sets (e.g., 80% training, 20% testing).
- Train a classification model on the training set to predict the applicationStatus label.
- Evaluate the model on the testing set and report the performance metrics (e.g., accuracy, precision, recall, F1-score).
- Provide any necessary data preprocessing steps and explain your choice of model.

## Submission
Please submit the following:
- A Jupyter notebook or script containing the code for data loading, preprocessing, model training, and evaluation.
- A brief explanation of your approach, including any insights gained from the data and the rationale behind your choice of model.
- Any additional comments or observations about the dataset or the task.
- requirements.txt

## Evaluation Criteria
Your submission will be evaluated based on the following criteria:
- Clarity and organization of the code. (10%)
- Correctness of the model implementation. (50%)
- Accuracy and thoroughness of the model evaluation. (20%)
- Explanation of the approach and choice of model. (20%)

