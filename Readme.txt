***************************
Tradeshow
2017 Geoffrey Pidcock - geoff@geoffpidcock.com
***************************

The following Git contains jupyter notebooks and other workfiles for a 2017 B2B tradeshow event.

The data set driving this analysis is a combination of anonymised CRM data (contact, lead, and opportunity), and event device data (NFC touchpoints representing a variety of information requests from the delegates).

The goal of this model is to predict conversion of a delegate into a business opportunity. 

Specific hypotheses: 
Does event lead scoring predict opportunity creation (interpretive model)?
What behavioural segments are in event device data?

Please contact Geoff Pidcock for a copy of the Data.


***************************
File Description:

TradeShow_HomeWork2.ipynb - "First Look" - General data munging and evaluation.
TradeShow_HomeWork3.ipynb - 
DT-calibration.png - example calibration curve from https://svds.com/classifiers2/
ExampleTree.dot - Present decision tree used for lead followup, based on heuristics used by a B2B biz
ExampleDecisionTree.png - viz of the .dot file
Sample-ROC.png - example ROC curve from https://svds.com/learning-imbalanced-classes/
scoring_tree_example.png - example lead scoring diagram sourced from http://dataconomy.com/2015/05/predictive-machine-learning-behind-the-scenes-at-fliptop-and-predictions-for-the-future-of-martech/

***************************
Data Description: 
v1
_Delegates.xlsx
'qr_uid'
'Customer' 
'Prospect' 
'Leaders Summit' 
'registered' 
'walk-in' 
'manual' 
'cancelled' 
'badge_printed' 
'Member Type' 
'Lead Contact ID' 
'Acount ID' 
'Job Function' 
'Job Level' 
'Industry' 
'Employees' 
'TOTAL Attendance Points' 
'TOTAL Engagement Points' 
'TOTAL Attendance and Engagement Points' 
'Oppty Created' 
'No. of Oppty'

