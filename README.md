# Clinical Trial Report Data Repository

### Predictive modeling of clinical trial terminations using feature engineering and embedding learning

In this study, we propose to use machine learning approach to understand terminated clinical trials. Our goal is to answer two fundamental questions: (1) what are common factors/markers associated to terminated clinical trials? and (2) how to accurately predict whether a clinical trial may be terminated or not? The answer to the first question provides effective ways to understand characteristics of terminated trials for stakeholders to better plan their trials; and the answer to the second question can direct estimate the chance of success of a clinical trial in order to minimize costs. By using 311,260 trials to build a testbed with 68,999 samples, we use feature engineering to create 640 features, reflecting clinical trial administration, eligibility, study information, criteria etc. Using feature ranking, we found that a handful of features, such as trial eligibility, trial inclusion/exclusion criteria, sponsor types etc., are found to be related to the clinical trial termination. By using sampling and ensemble learning, we achieve over 67% Balanced Accuracy and over 0.73 AUC (Area Under the Curve) scores to correctly predict clinical trial termination, indicating that machine learning can help achieve satisfactory prediction results for clinical trial study.

#### Clinical Trial Data

The data (including feature information) for the study can be found [here (zip file, 64 MB)](http://www.cse.fau.edu/~xqzhu/clinical/clinicalTrialsData.zip) 

The column NCTID refers to the Clinical trial's ID from the original online database, [ClincialTrials.gov](https://clinicaltrials.gov/). 

Information on the other variables in the dataset can be found in the published paper. 


### Understanding and Predicting COVID-19 Clinical TrialCompletionvs.Cessation

As of March 30 2021, over 5,193 COVID-19 clinical trials have been registered through Clinicaltrial.gov. Among them, 191 trials were terminated, suspended, or withdrawn (indicating the cessation of the study). On the other hand, 909 trials have been completed (indicating the completion of the study). In this study, we propose to study underlying factors of COVID-19 trial completion vs. cessation, and design predictive models to accurately predict whether a COVID-19 trial may complete or cease in the future. We collect 4,441 COVID-19 trials from ClinicalTrial.gov to build a testbed, and design four types of features to characterize clinical trial administration, eligibility, study information, criteria, drug types, study keywords, as well as embedding features commonly used in the state-of-the-art machine learning. Our study shows that drug features and study keywords are most informative features, but all four types of features are essential for accurate trial prediction. By using predictive models, our approach achieves more than 0.87 AUC (Area Under the Curve) score and 0.81 balanced accuracy to correctly predict COVID-19 clinical trial completion vs. cessation. Our research shows that computational methods can deliver effective features to understand difference between completed vs. ceased COVID-19 trials. In addition, such models can also predict COVID-19 trial status with satisfactory accuracy, and help stakeholders better plan trials and minimize costs.



## Authors

* **Magdalyn E. Elkin** 
* **Xingquan Zhu** 




