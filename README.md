# MISSION PREDICTABLE HACKATHON

Welcome to Team4: Annie Easley's github space. This was our submision to Mission Predictabale Hackaton challenge.
Let's rock!

## Problem Statement
We need a model that will tell us which at-risk individuals are likely to test positive for COVID-19 so that health workers can target testing resources and health education toward that population. For our initial study, we use the Mexico CoVID-19 dataset.

### Task:  
To create a model that successfully predicts if a person will test positive for COVID-19 or not.

### Background:  
Mexican Health Authorities released a robust patient dataset (Open Data - Mexico General Directorate of Epidemiology) that is updated daily.  We used the data file from August 13, 2020, containing 1.14 million patient records to train a binary classification model to predict COVID-19 test results. Two additional datasets were used, the Human Development Index and the Statista population dataset for the states in Mexico. The integrated file was split 80% for training, 20% for testing validation.

### Preprocessing needed

Locate rich patient dataset with broad coverage of patient health, demographics, test results and outcomes.

Prepare and clean datasets to remove null values and one hot encode relevant columns.

Use feature engineering to normalize the dataset features.

Run multiple iterations of experiments to explore the relevant features in the data.

Determine what questions and uncertainties are found in the data.

Evaluate the quality of the model to be tested against a significant portion of the data set not used to train the model (in this case 20% of the dataset).

### Performance:  
The model was able to accurately predict a positive result 68% of the time.

Link to Project Presentation
https://drive.google.com/file/d/1i532oms3TVirPDqHrMx-8FEBEbCKnF9M/view?usp=sharing

Link to Data Set
https://drive.google.com/drive/folders/1knIFc8Z_PpBPnxrpEHzNGa6Mz1S_QGyH?usp=sharing
