# Loan Predictor using Machine Learning
I worked as an intern on this project under Dlithe company(www.dlithe.com) 

Problem statememt: A company that provides loan wants to automate the loan eligibility process based on customer details provided while filling online application form. These details are Gender, Marital Status, Education, Income, Loan Amount, Credit History and others.

The dataset includes:
|Variable |	Description |
|----------|--------------|
|	Loan_ID |	Unique Loan ID |	
|	Gender	| Male/ Female |	
|Married	|Applicant married (Y/N)|
|Dependents|	Number of dependents|
|Education|	Applicant Education (Graduate/ Under Graduate)|
|Self_Employed |	Self employed (Y/N)|
|ApplicantIncome |	Applicant income|
|CoapplicantIncome|	Coapplicant income|
|LoanAmount |	Loan amount in thousands|
|Loan_Amount_Term |	Term of loan in months|
|Credit_History	|Credit history |
|Property_Area |	Urban/ Semi Urban/ Rural|
|Loan_Status |	Loan approved (Y/N)|

Solution: I have done data preprocessing by filling the null values of Loan Amount and Credit history and dropping the remaining null values. After encoding and scaling the features, machine learning algorithms of KNN, SVM, Logistic Regression and Naive Bayes are applied to obtain a descent accuracy.
The highest accuracy obtained is 81.65% using KNN model.
