# Warfarin and CKD

The research aims to evaluate the response of chronic kidney disease (CKD) Saudi patients to Warfarin in comparison to patients on Warfarin who have normal kidney functions.

## Investigation Overview

> The research aimed to evaluate the response of chronic kidney disease (CKD) Saudi patients to Warfarin in comparison to patients on Warfarin who have normal kidney functions. 

## Dataset Overview

> The final data-set file included three different excel sheets. The first sheet contained the patients' Characteristics. Warfarin doses and the international normalized ratio (INR) values for each patient were collected into the second sheet. The third sheet included the information about whether or not each patient developed a bleeding (minor or major) or a venous thromboembolism (VTE) event. 

## Results
Four tables are produced:
1. Patients Demographics 
2. Baseline Differences between CKD patients and NKF patients 
3. Outcome Differences between CKD patients and NKF patients 
4. Linear regression model about the expected Warfarin dose that is needed to achieve the therapeutic range which can be predicted the   for any patient given his/her age, weight and CKD status by the following equation:

>> Predicted Dose = 4.4 - Age×0.037 + Weight×0.042 (if the patient is a CKD patient subtract 1.25)

This is based on the data of the patients in the study. I think, however, that the equation will only correctly estimate the needed dose in only 17% of patients. 


## Dependencies    
The data were managed and analysed in Python 3.7.
