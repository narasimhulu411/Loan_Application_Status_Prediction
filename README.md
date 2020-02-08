# Loan_Application_Status_Prediction
The Banks want to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.
Description of the dataset:
Dataset has information about loan applicants data such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others

File Format :csv

Rows :614

Columns :13

Target Variable :Loan_Status

Attribute Information :
Loan_ID : Unique Loan ID

Gender : Applicant's Gender (Male/ Female)

Married : Marital status((Y/N))

Dependents : Number of dependents

Education : Applicant Education (Graduate/ Under Graduate)

ApplicantIncome : Applicant's Income

CoapplicantIncome : Coapplicant's Income

LoanAmount : Loan Amount in thousands

Loan_Amount_Term : Term of loan in months

Credit_History : Credit_History of applicant

Property_Area : Urban/ Semi Urban/ Rural

Loan_Status : lLoan approved (Y/N)

Loan status prediction extra information :
Below are some of the factors which I think can affect the Loan Approval (dependent variable for this loan prediction problem):

Salary : Applicants with high income should have more chances of loan approval.

Previous history: Applicants who have repayed their previous debts should have higher chances of loan approval.

Loan amount: Loan approval should also depend on the loan amount. If the loan amount is less, chances of loan approval should be high.

Loan term: Loan for less time period and less amount should have higher chances of approval.

EMI: Lesser the amount to be paid monthly to repay the loan, higher the chances of loan approval.

These are some of the factors which i think can affect the target variable, you can come up with many more factors

Objective :
To build a model which predicts whether the applicant's loan will be approved or rejected.

Constraints :
1.Acceptable with little latency.

2.Need good Exploratory Data Analysis.

Type of Machine Learning Problem :
Binary Classification

Performace Metrics :
Try with as many as possible metrics.

1.Accuracy

2.Confusion Matrix

3.Precision and Recall

4.F1 score

5.ROC curvers

6.AUC

