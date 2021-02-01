# Predictive modeling of clinical trial terminations using feature engineering and embedding learning

In this study, we propose to use machine learning approach to understand terminated clinical trials. Our goal is to answer two fundamental questions: (1) what are common factors/markers associated to terminated clinical trials? and (2) how to accurately predict whether a clinical trial may be terminated or not? The answer to the first question provides effective ways to understand characteristics of terminated trials for stakeholders to better plan their trials; and the answer to the second question can direct estimate the chance of success of a clinical trial in order to minimize costs. By using 311,260 trials to build a testbed with 68,999 samples, we use feature engineering to create 640 features, reflecting clinical trial administration, eligibility, study information, criteria etc. Using feature ranking, we found that a handful of features, such as trial eligibility, trial inclusion/exclusion criteria, sponsor types etc., are found to be related to the clinical trial termination. By using sampling and ensemble learning, we achieve over 67% Balanced Accuracy and over 0.73 AUC (Area Under the Curve) scores to correctly predict clinical trial termination, indicating that machine learning can help achieve satisfactory prediction results for clinical trial study.

## Clinical Trial Data

The data for the study can be found [here](Data/ClinicalTrialTerminations.csv) 

The column NCTID refers to the origional ID from the origional online database, [ClincialTrials.gov](https://clinicaltrials.gov/). 

Information on the other variables in the dataset can be found in the published paper. 


## Authors

* **Magdalyn E. Elkin** 
* **Xingquan Zhu** 




