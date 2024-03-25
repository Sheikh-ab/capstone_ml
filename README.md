### capstone_ml
 In this  application, I will compare the 
KNeighborsClassifier
SVC
DecisionTreeClassifier
RandomForestClassifier
AdaBoostClassifier
GradientBoostingClassifier
SGDClassifier
 


ObesityDataSet_raw_and_data_sinthetic.csv
**Sheikh M**

#### Executive summary
Will train the model on obesity dataset in prdicting user's Classifiction {Insufficient_Weight,Normal_Weight,Overweight_Level_I,Overweight_Level_II,Obesity_Type_I,Obesity_Type_II,Obesity_Type_III}. 


#### Rationale

Model can predict how to classify the individual as 
Insufficient_Weight 
Normal_Weight
Overweight_Level_I
Overweight_Level_II
Obesity_Type_I
Obesity_Type_II
Obesity_Type_III

#### Research Question
What are factors that effect Obesity based on the data provided

#### Data Sources

Data: https://www.kaggle.com/code/pmrich/obesitydataset-eda-data-prep-ml-hypertuning/input


#### Methodology

KNeighborsClassifier
SVC
DecisionTreeClassifier
RandomForestClassifier
AdaBoostClassifier
GradientBoostingClassifier
SGDClassifier

#### Results
Results from the Finding are below
- KNeighborsClassifier()
model score: 0.841
                     precision    recall  f1-score   support

Insufficient_Weight       0.73      0.95      0.82        64
      Normal_Weight       0.77      0.42      0.55        78
     Obesity_Type_I       0.87      0.96      0.91        74
    Obesity_Type_II       0.96      0.96      0.96        82
   Obesity_Type_III       0.99      1.00      0.99        81
 Overweight_Level_I       0.69      0.76      0.72        74
Overweight_Level_II       0.85      0.84      0.85        75

           accuracy                           0.84       528
          macro avg       0.84      0.84      0.83       528
       weighted avg       0.84      0.84      0.83       528

- SVC(C=0.025, probability=True)
model score: 0.473
                     precision    recall  f1-score   support

Insufficient_Weight       0.76      0.89      0.82        64
      Normal_Weight       0.80      0.21      0.33        78
     Obesity_Type_I       0.22      0.99      0.36        74
    Obesity_Type_II       1.00      0.29      0.45        82
   Obesity_Type_III       0.99      0.99      0.99        81
 Overweight_Level_I       0.00      0.00      0.00        74
Overweight_Level_II       0.00      0.00      0.00        75

           accuracy                           0.47       528
          macro avg       0.54      0.48      0.42       528
       weighted avg       0.55      0.47      0.42       528

- DecisionTreeClassifier()
model score: 0.936
                     precision    recall  f1-score   support

Insufficient_Weight       0.97      0.97      0.97        64
      Normal_Weight       0.91      0.88      0.90        78
     Obesity_Type_I       0.85      0.99      0.91        74
    Obesity_Type_II       0.99      0.93      0.96        82
   Obesity_Type_III       0.99      0.99      0.99        81
 Overweight_Level_I       0.89      0.91      0.90        74
Overweight_Level_II       0.97      0.89      0.93        75

           accuracy                           0.94       528
          macro avg       0.94      0.94      0.94       528
       weighted avg       0.94      0.94      0.94       528

- RandomForestClassifier()
model score: 0.936
                     precision    recall  f1-score   support

Insufficient_Weight       1.00      0.95      0.98        64
      Normal_Weight       0.83      0.94      0.88        78
     Obesity_Type_I       0.96      0.97      0.97        74
    Obesity_Type_II       1.00      0.96      0.98        82
   Obesity_Type_III       0.99      0.99      0.99        81
 Overweight_Level_I       0.90      0.82      0.86        74
Overweight_Level_II       0.89      0.91      0.90        75

           accuracy                           0.94       528
          macro avg       0.94      0.93      0.94       528
       weighted avg       0.94      0.94      0.94       528

- AdaBoostClassifier()
model score: 0.294
                     precision    recall  f1-score   support

Insufficient_Weight       0.57      0.98      0.72        64
      Normal_Weight       0.38      0.06      0.11        78
     Obesity_Type_I       0.14      0.31      0.19        74
    Obesity_Type_II       0.00      0.00      0.00        82
   Obesity_Type_III       0.00      0.00      0.00        81
 Overweight_Level_I       0.30      0.86      0.44        74
Overweight_Level_II       0.00      0.00      0.00        75

           accuracy                           0.29       528
          macro avg       0.20      0.32      0.21       528
       weighted avg       0.19      0.29      0.19       528

- GradientBoostingClassifier()
model score: 0.958
                     precision    recall  f1-score   support

Insufficient_Weight       0.95      0.98      0.97        64
      Normal_Weight       0.90      0.91      0.90        78
     Obesity_Type_I       0.95      0.99      0.97        74
    Obesity_Type_II       0.99      0.98      0.98        82
   Obesity_Type_III       1.00      0.99      0.99        81
 Overweight_Level_I       0.94      0.88      0.91        74
Overweight_Level_II       0.97      0.99      0.98        75

           accuracy                           0.96       528
          macro avg       0.96      0.96      0.96       528
       weighted avg       0.96      0.96      0.96       528

- SGDClassifier()
model score: 0.680
                     precision    recall  f1-score   support

Insufficient_Weight       0.91      1.00      0.96        64
      Normal_Weight       0.70      0.68      0.69        78
     Obesity_Type_I       0.36      0.88      0.51        74
    Obesity_Type_II       0.91      0.96      0.93        82
   Obesity_Type_III       1.00      0.99      0.99        81
 Overweight_Level_I       0.53      0.24      0.33        74
Overweight_Level_II       0.00      0.00      0.00        75

           accuracy                           0.68       528
          macro avg       0.63      0.68      0.63       528
       weighted avg       0.63      0.68      0.63       528


#### Next steps
Add more visualization 
Predict on new data to check the accuracy of the model

#### Outline of project
Main notebook is 
-- Capstone_1.pynb


##### Contact and Further Information

