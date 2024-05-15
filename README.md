# Reoperation due to bleeding after CABG machine learning code


39 Objectives: In the present study, we compared the accuracy of different machine learning (ML)
40 models with logistic regression (LR) in predicting the risk of reoperation for bleeding (RB) after 
41 coronary artery bypass graft (CABG) surgery. 
42 Methods: A total of 25,224 patients who underwent CABG were included in the study. Reoperation 
43 for bleeding or tamponade was considered the primary endpoint. The dataset was divided with a 
44 70:30 ratio into train and test splits stratified by the target variable. Due to the target imbalance, 
45 the synthetic minority oversampling technique (SMOTE) was used to artificially increase the 
46 number of observations with RB in the training set. Several ML and LR models were trained and 
47 validated on the training set. An online calculator was developed and deployed using the LR model.
48 Results: From the original total dataset, 807 (3.2%) patients required RB. Male sex, current cigarette 
49 smoking, history of renal failure, antiplatelet use, urgent/emergent, and on-pump surgery were 
50 more common among patients requiring RB. ROC AUCs for the blended model was highest 
51 (61.67%, 95%CI: 58.21% - 65.15%), followed by LightGBM (61.56%, 95%CI: 58.10 - 65.04). The 
52 logistic regression had a similar AUC (61.23%, 95%CI: 57.69% - 64.77%). 
53 Conclusions: In small datasets, simpler models like LR may have similar accuracy to ML models 
54 while providing better model interpretability. Older age, male sex, high preoperative creatinine 
55 levels, concomitant valve surgery, renal failure, and on-pump surgery were associated with a higher 
56 risk of RB after CABG.
