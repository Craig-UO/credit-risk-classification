# credit-risk-classification
Homework 20
The main directory contains only the README.

Inside the Credit_Risk directory is the starter Notebook provided by the instructor and the credit_risk_classificiaton.ipynb file which is the student's submission.

Data provided by the instructor for the challenge are in the Resources directory.

---------------------------------------------------------------------------------------------------------------
CREDIT RISK ANALYSIS REPORT

The purpose of this analysis is to use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.  Each borrower evaluated will be assigned a binary result of either "healthy" or "high-risk."

The precision for healthy loans is very high at 99.5%, so nearly all of the loans the model decides are healthy loans are in fact healthy (in the test data).  These far outnumber the high-risk loans on whole, however.  The precision for the high-risk loans is worse at 85%, so the model is tagging some high-risk loans as healthy.

Recall for healthy loans is very high at 99%.  Again, healthy loans far outnumber the high-risk loans in the data set, so a model that is too likely to call a loan healthy would easily find all the actually healthy ones.  The recall for the high-risk loans is again worse at only 91%, so this is classifying about 10% of the high-risk loans as healthy.

The recommendation would be to tune this model such that the total cost of bad loans that are made, and good loans that are declined to be made, is minimized.  Further financial information would be needed from the institution to determine that value.  It's likely that the most critical value for this model is the recall for high-risk loans (so as not to misclassify those as healthy when they are not), so it's likely the lending instution would want more work to be done to increase recall for high-risk loans.
