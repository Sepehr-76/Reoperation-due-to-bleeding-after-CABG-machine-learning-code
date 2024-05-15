# Reoperation due to bleeding after CABG machine learning code


Objectives: In the present study, we compared the accuracy of different machine learning (ML)
models with logistic regression (LR) in predicting the risk of reoperation for bleeding (RB) after 
coronary artery bypass graft (CABG) surgery. 
Methods: A total of 25,224 patients who underwent CABG were included in the study. Reoperation 
for bleeding or tamponade was considered the primary endpoint. The dataset was divided into a 
70:30 ratio into train and test splits stratified by the target variable. Due to the target imbalance, 
the synthetic minority oversampling technique (SMOTE) was used to artificially increase the 
number of observations with RB in the training set. Several ML and LR models were trained and 
validated on the training set. An online calculator was developed and deployed using the LR model.
Results: From the original total dataset, 807 (3.2%) patients required RB. Male sex, current cigarette 
smoking, history of renal failure, antiplatelet use, urgent/emergent, and on-pump surgery were 
more common among patients requiring RB. ROC AUCs for the blended model was the highest 
(61.67%, 95%CI: 58.21% - 65.15%), followed by LightGBM (61.56%, 95%CI: 58.10 - 65.04). The 
logistic regression had a similar AUC (61.23%, 95%CI: 57.69% - 64.77%). 
Conclusions: In small datasets, simpler models like LR may have similar accuracy to ML models 
while providing better model interpretability. Older age, male sex, high preoperative creatinine 
levels, concomitant valve surgery, renal failure, and on-pump surgery were associated with a higher 
risk of RB after CABG.
