# Loan-Approval-Prediction

## Predict Loan Eligibility for Dream Housing Finance company

Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan. Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 

## Data Dictionary

**Train file:** CSV containing the customers for whom loan eligibility is known as 'Loan_Status'
![Capture](https://user-images.githubusercontent.com/62636740/110599705-25e2aa80-81a9-11eb-8ae2-0240234a8d7e.PNG)

**Test file:** CSV containing the customer information for whom loan eligibility is to be predicted
![Capture2](https://user-images.githubusercontent.com/62636740/110599819-47439680-81a9-11eb-8854-48ed16291300.PNG)

**Submission file format**

![Capture3](https://user-images.githubusercontent.com/62636740/110599967-6cd0a000-81a9-11eb-880b-46d9f4df01ee.PNG)

## Evaluation Metric
Your model performance will be evaluated on the basis of your prediction of loan status for the test data (test.csv), which contains similar data-points as train except for the loan status to be predicted. Your submission needs to be in the format as shown in sample submission. We at our end, have the actual loan status for the test dataset, against which your predictions will be evaluated. We will use the Accuracy value to judge your response.

## Model & Their Accuracy

**1. Decision Tree Classifier:-(Without Adding Max Depth & Min Sample Leaf)**
![Capture4](https://user-images.githubusercontent.com/62636740/110601182-ae157f80-81aa-11eb-8f55-b528c70bc1bf.PNG)

**a. DTC Accurcay With Max Depth Chart:**
![Capture5](https://user-images.githubusercontent.com/62636740/110601274-c71e3080-81aa-11eb-9360-8ccaf5fb60c5.PNG)

**b. DTC Accuracy With Min Sample Leaf:**
![Capture6](https://user-images.githubusercontent.com/62636740/110601378-def5b480-81aa-11eb-8c18-13392d39b863.PNG)

**2. Decision Tree Classifier:-(With Adding Max Depth=3 & Min Sample Leaf=35)**

![Capture7](https://user-images.githubusercontent.com/62636740/110601622-254b1380-81ab-11eb-91bb-02b00cb5611c.PNG)

**3. Logistic Regression:(Applying Threshold Value)**
![Capture8](https://user-images.githubusercontent.com/62636740/110601870-66432800-81ab-11eb-9b49-320f6982adca.PNG)

**a. Logistic Regression:(Applying Threshold Value=0.4)**

![Capture9](https://user-images.githubusercontent.com/62636740/110602041-95f23000-81ab-11eb-9d1f-946c2f2dd8bd.PNG)

## Librarey Used:
![scikit-learn-logo-small](https://user-images.githubusercontent.com/62636740/110602235-cafe8280-81ab-11eb-94bd-e5ba4215e1c0.png)

[Graphviz Library Link Here](https://github.com/xflr6/graphviz/tree/54b4eecd0f2cc2ac356943ecc1f042abb6e627d2)
