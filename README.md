# Pattern-Discovery-and-Predictive-Analytics
Data analytics processes using Weka
## Association rule mining: 
subset of the attributes were used to mine some interesting patterns. To rank the interestingness of the rules extracted, I used support, confidence and lift. 

## Classification: 
Using the "income" range/bracket as the target variable, two decision tree models were built: 
1) one uses a list of attributes selected based random chance 
2) the other uses attribute selection based on information gain. 
The performance of the 2 trees were compared using 10 fold cross-validation.

## Clustering: 
K means clusterning algorith run  on the data.

# Data reduction: 
Performed numerosity reduction using sampling and feature reduction with PCA(principle component analysis). 
Trained a model on the reduced data and another model on the original data. Compared the performance of the two models using 10 fold cross-validation.
