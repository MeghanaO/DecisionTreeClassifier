# DecisionTreeClassifier
How to create decision tree in python

The attached 2 jupyter notebook files shows the python commands to create a decision tree and evaluate performance metrics from the decision tree classifier that is created.
Brief description of 2 notebook files is as follows:
DecisionTree_MinLeafSamples_3.ipynb :
  Here first the dataset from an excel is imported using python pandas framework and a result dataset is created.
  Then a decision tree classifier is created from this dataset object using the DecisionTree package
  Performance metrics like accuracy , precision are determined.
  
DecisionTree_MinLeafSamples_8.ipynb :
  The difference of this program with the above is that, here the input features are assigned values ranging from 0 to 4 based on their interval using numpy package qcut method
  This changes the dataset and also the performance
  
 DecisionTree_KFold.ipynb :
  KFold testing is performed on a dataset using different available in built python methods like GridSearchCV, StratifiedKFold,           RandomizedSearchCV
