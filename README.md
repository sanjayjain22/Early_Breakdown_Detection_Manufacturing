##### DATASET PROVIDED BY PROCESSMINER INC, ATLANTA.
Early Detection of breakdowns in paper manufacturing resulting in huge savings.

## Early_Breakdown_Detection_Manufacturing
![alt text](https://github.com/sanjayjain22/Early_Breakdown_Detection_Manufacturing/blob/master/Resources/paper_manufacturing.png?raw=true)

 Typical paper manufacturing setup.
 
## Motivation
A typical paper manufacturing plant faces at least one sheet break a day. Each such break can cost upwards of $25,000. Sheet breaks are known to cost $6-8 Million a year in a plant. Considering the worldwide paper industries, this translates to loss revenue of $3 billions every year.

Additionally, parts of paper machines have hazardous conditions. Resuming the operations after a sheet break requires operators to face such hazards.

Developing a solution to address this problem can save costs and reduce work hazards.
## SOLUTION PROPOSAL
* We intend to build a model which can detect these breakdowns before they occur, so that the operator can minimize the risk of breakdowns by adjusting the variables.
 
## DATASET
The provided data has,
* 18,398 records.
* Columns:
– time: the timestamp of the row
– y: the binary response variable. There are only 124 rows with y = 1, rest are y = 0.
– x1-x61: predictor variables. All the predictors are continuous variables, except x28 and x61. x61 is a binary variable, and x28 is a
categorical variable. All the predictors are centered. 
Besides, the predictors are a mixture of raw materials and process variables. 
Their descriptions are omitted for data anonymity.

## Feature Engineering & Modelling
 *  Feature engineering and modelling is explained in the Ipython notebook attatched.

## Results 
 
 ![alt text](https://github.com/sanjayjain22/Early_Breakdown_Detection_Manufacturing/blob/master/Resources/confusion_matrix.png?raw=true)
 
 * With a Recall of 16/40 = 0.4 and a Precision of 16/145 = 0.1103, Can result in significant savings for paper manufacturing companies.
 
 
 
 


