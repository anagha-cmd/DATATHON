# DATATHON
Voter prediction based on DPhi dataset

**Content**

A tax is a compulsory financial charge or some other type of levy imposed on a taxpayer (an individual or legal entity) by a governmental organization in order to fund government spending and various public expenditures.

**Objective**

You are required to build a machine learning model that would predict the political party to which a taxpayer belongs to.

About the Data
The dataset contains information about US taxpayers. There are 10 independent columns and 1 dependent column. This dataset includes attributes like household income, household debt level, if the taxpayer is married or not, how many cars their household has, if they filed their taxes in the last three years or not. Some of the attribute informations are given below:

To load the training data in your jupyter notebook, use the below command:

import pandas as pd

tax_data  = pd.read_csv("https://raw.githubusercontent.com/dphi-official/Datasets/master/tax_payers/train_set_label.csv" )

Data Description
HHI: Household income

HHDL: Household debt level

Married: There are three categories for a taxpayer 0, 1, 2 with regards to marriage.

PoliticalParty: Name of the political party

CollegeGrads: Grade in College out of 5

AHHAge: Average household age

cars: number of cars in house

Filed in YYYY: Tax filed in given year YYYY

Saving Prediction File & Sample Submission
You can find more details on how to save a prediction file here: https://discuss.dphi.tech/t/how-to-submit-predictions/548

Sample submission: You should submit a CSV file with a header row and the sample submission can be found below.

prediction

Democrat

Independent

Republican

Republican

Independent

Democrat

Republican

.

.

Etc.

Note that the header name should be prediction else it will throw an evaluation error. A sample submission file can be found here

Test Dataset
Load the test data (name it as test_data). You can load the data using the below command.

test_data = pd.read_csv('https://raw.githubusercontent.com/dphi-official/Datasets/master/tax_payers/test_set_label.csv')

hv5.csv is the final submission
