**Project Overview**



Credit Risk Segmentation using CatBoost



**Objective**



Predict customers with potential 30+ DPD within MOB3 MOB6 and identify high risk customer segments.



**Methodology**

* Feature Engineering
* CatBoost Classification
* SHAP Analysis
* Risk Segmentation



**Important Features**

* Previous Cycle
* Ever Collection History
* Branch Area


**Resutl**

===== DH1 =====
              precision    recall  f1-score   support

           0       0.98      0.99      0.99    168477
           1       0.07      0.04      0.05      2762

    accuracy                           0.98    171239
   macro avg       0.53      0.51      0.52    171239
weighted avg       0.97      0.98      0.97    171239

             Pred Good  Pred Bad
Actual Good     167167      1310
Actual Bad        2664        98
ROC AUC Score: 0.6737386337265735

===== DH2 =====
              precision    recall  f1-score   support

           0       0.98      0.98      0.98     77755
           1       0.06      0.07      0.06      1444

    accuracy                           0.96     79199
   macro avg       0.52      0.53      0.52     79199
weighted avg       0.97      0.96      0.96     79199

             Pred Good  Pred Bad
Actual Good      76014      1741
Actual Bad        1338       106
ROC AUC Score: 0.6552939474815329

===== DH3 =====
              precision    recall  f1-score   support

           0       0.99      1.00      0.99    113858
           1       0.00      0.00      0.00      1543

    accuracy                           0.99    115401
   macro avg       0.49      0.50      0.50    115401
weighted avg       0.97      0.99      0.98    115401

             Pred Good  Pred Bad
Actual Good     113838        20
Actual Bad        1543         0
ROC AUC Score: 0.6201762335495224

===== DH4 =====
              precision    recall  f1-score   support

           0       0.99      1.00      1.00     68789
           1       0.00      0.00      0.00       639

    accuracy                           0.99     69428
   macro avg       0.50      0.50      0.50     69428
weighted avg       0.98      0.99      0.99     69428

             Pred Good  Pred Bad
Actual Good      68789         0
Actual Bad         639         0
ROC AUC Score: 0.6492802114178688

===== DH5 =====
              precision    recall  f1-score   support

           0       0.99      1.00      1.00     96363
           1       0.00      0.00      0.00       828

    accuracy                           0.99     97191
   macro avg       0.50      0.50      0.50     97191
weighted avg       0.98      0.99      0.99     97191

             Pred Good  Pred Bad
Actual Good      96360         3
Actual Bad         828         0
ROC AUC Score: 0.6985190258593951



**Tools**

* Python
* Pandas
* CatBoost
* SHAP
* Scikit-Learn

