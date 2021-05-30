Credit Card Lead Prediction
Happy Customer Bank is a mid-sized private bank that deals in all kinds of banking products, like Savings accounts, Current accounts, investment products, credit products, among other offerings.



The bank also cross-sells products to its existing customers and to do so they use different kinds of communication like tele-calling, e-mails, recommendations on net banking, mobile banking, etc. 



In this case, the Happy Customer Bank wants to cross sell its credit cards to its existing customers. The bank has identified a set of customers that are eligible for taking these credit cards.



Now, the bank is looking for your help in identifying customers that could show higher intent towards a recommended credit card, given:

Customer details (gender, age, region etc.)
Details of his/her relationship with the bank (Channel_Code,Vintage, 'Avg_Asset_Value etc.)
Data Dictionary
Train Data
Variable

Definition

ID

Unique Identifier for a row

Gender

Gender of the Customer

Age

Age of the Customer (in Years)

Region_Code

Code of the Region for the customers

Occupation

Occupation Type for the customer

Channel_Code

Acquisition Channel Code for the Customer  (Encoded)

Vintage

Vintage for the Customer (In Months)

Credit_Product

If the Customer has any active credit product (Home loan,

Personal loan, Credit Card etc.)

Avg_Account_Balance


Average Account Balance for the Customer in last 12 Months

Is_Active

If the Customer is Active in last 3 Months

Is_Lead(Target)

If the Customer is interested for the Credit Card

0 : Customer is not interested

1 : Customer is interested


Test Data
Variable

Definition

ID

Unique Identifier for a row

Gender

Gender of the Customer

Age

Age of the Customer (in Years)

Region_Code

Code of the Region for the customers

Occupation

Occupation Type for the customer

Channel_Code

Acquisition Channel Code for the Customer  (Encoded)

Vintage

Vintage for the Customer (In Months)

Credit_Product

If the Customer has any active credit product (Home loan,

Personal loan, Credit Card etc.)

Avg_Account_Balance


Average Account Balance for the Customer in last 12 Months

Is_Active

If the Customer is Active in last 3 Months

Sample Submission
This file contains the exact submission format for the predictions. Please submit CSV file only.

Variable	Definition
ID	Unique Identifier for a row
Is_Lead	(Target) Probability of Customer showing interest (class 1)




How to Make a Submission?
All Submissions are to be done at the solution checker tab.
For a step by step view on how to make a submission check the below video



Evaluation
The evaluation metric for this competition is roc_auc_score across all entries in the test set.



Public and Private Split
Test data is further divided into Public 30% and Private 70%

Your initial responses will be checked and scored on the Public data.
The final rankings would be based on your private score which will be published once the competition is over.
 

Guidelines for Final Submission
Please ensure that your final submission includes the following:

Solution file containing the predicted probabilities of Response for the customers
A Zipped file containing code & approach (Note that both code and approach document are mandatory for shortlisting)
Code: Clean code with comments on each part
Approach: Please share your approach to solve the problem (doc/ppt/pdf format). It should cover the following topics:
A brief on the approach, which you have used to solve the problem.
What data-preprocessing / feature engineering ideas really worked? How did you discover them?
What does your final model look like? How did you reach it?
 

How to Set Final Submission?


Hackathon Rules
The final standings would be based on private leaderboard score.
Setting the final submission is recommended. Without a final submission, the submission corresponding to best public score will be taken as the final submission
Use of external data is prohibited
Use of ID variable is not allowed as part of the model
You can only make 10 submissions per day
Entries submitted after the contest is closed, will not be considered
The code file pertaining to your final submission is mandatory while setting final submission
Throughout the hackathon, you are expected to respect fellow hackers and act with high integrity.
Analytics Vidhya holds the right to disqualify any participant at any stage of the competition if the participant(s) are deemed to be acting fraudulently.
Use of multiple Login IDs will lead to immediate disqualification
Data
  
