# Telco_Churn
This is a personal project that I carried out to study the probabilities of churn that TELCO faces.

TELCO inc is a phoning company facing a churn problem. They collected a dataset on their past customers in order to: 
1/ rank their customers according to the probability of churn 
2/ tell who are the clients they should contact and what should be the relevant personalized discount to propose in order to maximize the future profit of TELCO Inc (tradeoff between churn prevention and reduced profit per customer after discount). 
There is a fixed cost of 10€ to contacting a customer.  
The data set contains 2 files: 
1/ a training set, including the labels in the column ”CHURNED” 
2/ a test set with the same columns, but without the labels. 

You will find a csv file 'churn_predictions' containing the following columns: 
1/ CUSTOMER_ID 
2/ CHURN_PROBABILITY 
3/ CHURN_LABEL (either ‘LEAVE’ or ‘STAY’) 
4/ CLIENT_TO_CONTACT (either ‘YES’ or ‘NO’) 
5/ DISCOUNT (proposed maximum discount for the customer) 
The metric used to validate the model will be the ROC AUC. 
