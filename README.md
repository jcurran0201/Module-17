# Module-17 Credit Risk

## Overview of the loan prediction risk analysis 
The purpose of the project is to predict Credit Risk using Machine Learning. 
## Results 
## Formulas
recall score= True positive/(true positive + false negative)
### random oversampler
accuracy score = 0.620091373871424 
precision = 0.99  
recall score= 10998/(10998+52)=0.99529411764
### SMOTE
accuracy score = 0.6535437591404087
precision =  0.99 
recall score= 11553/(11553+ 55)=0.99526188835
### Cluster Centroids. 
accuracy score = 0.5726206735398511
precision =  0.99
recall score= 8389/(8389+57)= 0.99325124319
### SMOTEENN. 
accuracy score = 0.6347260999713953
precision =  0.99
recall score= 10712/(10712+56)=0.99479940564
### BalancedRandomForestClassifier 
accuracy score = 0.7781131779010599
precision =  0.99
recall score= 15621/(15621+56)= 0.99642788798
### EasyEnsembleClassifier 
accuracy score =  0.9010730789529875
precision =  0.99
recall score= 16289/(16289+74)=0.9954776019
## Summary: 
## Summary of Results  
The percision and recall scores are all nearly identical, but EasyEnsembleClassifier has the best accuracy score far and away. 
### recommendation on which model to use 
I recommend EasyEnsembleClassifier because of it's high accuracy score. 
