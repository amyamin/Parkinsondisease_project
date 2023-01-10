# Analysis of Speech features as an Early Biomarker of Parkinson's Disease in REM Sleep Behaviour Disorder Patients

## Description
This code uses **K-nearest neighbourhoods classification** to determine whether **combinations of speech features** can **predict early Parkinson's Disease in REM sleep behaviour disorder.**

It determines what combination of speech features are most distinct between Early untreated Parkinson's Disease patients and Healthy controls and hopes to indicate **whether certain speech features can be used as a biomarker for Parkinson's Disease.**

## Dependencies
numpy

matplotlib

seaborn

scikit-learn (1.2.0)

## Installing 

**The main script to be downloaded is:**

PDprediction.ipynb

**The modules that also must be downloaded that the script calls are:**

plot.py

## Executing Program

The script uses the dataset: parkinsondata.csv which is uploaded to this github repository.

1. Run through the script in order and follow the annotations.
2. Where applicable you can change combinations of speech features and decide your own, make sure to change x values where relevant (modelling and graphs).


## Results
After classification of motor symptoms using UPDRS III >3 indicates initial parkinsonism I found that 70% of patients were motor positive, and 30% were motor negative (Figure 1). Upon graphical exploration of speech features (Figure 2), I chose to go forward with **Duration  of  pause  intervals and Duration  of  unvoiced  stops (Monologue)** (Fig 2B). I ran the KNN classification and the model had an accuracy of 0.8 (Figure 3). I then used the model on RBD patients to predict whether the results from the selected speech features might indicate signs of early Parkinson's Disease (Figure 4). Visualisation of the predicted Parkinson's disease status from the model showed the spread of results in RBD patients (Figure 5). I found that 43% of RBD patients who have motor positive symptoms were predicted to potentially show signs of early Parkinson's. Whilst, 33%  of RBD patients who have motor negative symptoms were predicted to potentially show signs of early Parkinson's (Figure 6). 
This indicates that speech features may accurately predict potential early Parkinson's disease before the generation of motor dysfunction. 

## Conclusion 
Here I showed that speech features may be a potential early biomarker for Parkinson's Disease in patients who have disorders that increase their likelihood for developing this neurodegenerative disease such as REM sleep behaviour disorder.

## References 
Hlavnička, J., Čmejla, R., Tykalová, T. et al. Automated analysis of connected speech reveals early biomarkers of Parkinson’s disease in patients with rapid eye movement sleep behaviour disorder. Sci Rep 7, 12 (2017). https://doi.org/10.1038/s41598-017-00047-5



