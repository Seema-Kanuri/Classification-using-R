# Classification-using-R
The goal is to classify the customers and predict if the customer will subscribe. 
The data is related with direct marketing campaigns of a Portuguese banking institution. 
The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required,
in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.


Data Set Information:

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

There are four datasets:
1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
2) bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs).
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs).


The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM).
The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).


Methodology 
Step 1: Business Problem
Step 2: Analytics Objective
Step 3: Data Preparation /Data Pre processing
Step 4: Imputing the null values
Step 5: Feature Selection
Step6: Imbalance Data treatment
Step7 : Model Selection


Analysed the campaign data available and build a classification model…… without calls data

During any campaign, it is important to target the right customers. In this case its telemarketing campaign and if the customer doesn't want the product than the call would be ineffective. So it's best to classify the customer beforehand and call that customer who has a higher propensity to convert this will save marketing team time, calls, and money.


