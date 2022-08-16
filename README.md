# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals
Automating the loan eligibility based on customer details

## Hypothesis
1. Applicants having a credit history 
2. Applicants with higher applicant and co-applicant incomes
3. Applicants with higher education level
4. Properties in urban areas with high growth perspectives
+5. Applicants with higher income per person in the family (considering #of dependents)
+6. Applicants with lower loan amount in application
+7. Applicants with high savings (data not provided here)

## EDA 
For loan approval, credit_history is required. (no matter it is good or not - there is no credit score in the dataset. What's given in the data is whether credit history exists or not)

median total income is higher for the one who got the loan approved than who did not.

Loan approval rate for 'Semiurban area' was higher than 'Rural area' or 'Urban'. (possibly due to high growth potential in value)



## Process
Data cleansing: 
numerical values – mean()
Categorical values – mode()

Feature engineering: 
Total income = applicant income + co-applicant income

Modeling: 
LogisticRegression(), KNeighborsClassifier(), GaussianNB(), DecisionTreeClassifier(), SVC()


## Results/Demo
(fill in your model's performance, details about the API you created, and (optional) a link to an live demo)
attached in powerpoint file.

## Challanges 
Pipeline error
  Easy to follow the steps, however once I get an error, it is hard to find where to fix it 
  Even though I set a simpleimputer to replace null values, it didn’t work(!)


## Future Goals
(what would you do if you had more time? are there any potential issues/biases with your model/use case?)
