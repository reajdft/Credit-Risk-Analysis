# Risky Business - Loan Default Modelling
### Resampling Workbook Includes:
* Random Oversampling
* SMOTE Oversampling
* Cluster Centroid Undersampling
* SMOTEENN Combination Sampling
### Results
* SMOTE oversampling reveleaded the strongest **balanced accuracy** score (.65)
* SMOTE oversampling reveleaded the strongest **recall** score (.68)
* Random oversampling reveleaded the strongest **geometric mean** score (.67)
### Notes
* Dataset contained 95 feature variables, not scalared which may be leading to divergent results from the starter file


### Ensemble Includes:
* Balanced Random Forest Classifier
* Gradient Boost Classifier
* AdaBoost Classifier (used generic code from the web as this doesn't appear to have been covered in class)
### Results
* Adaboost yielded the strongest **balanced accuracy** score (.99)
* Adadboost generated the strongest **recall** score (1)
* Random Forest delivered the strongest **geometric mean** score (.79)
* Top 3 Features:
(1) total_rec_prncp	0.081629
(2) last_pymnt_amnt	0.064709
(3) total_pymnt_inv	0.057475