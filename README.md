# mammogram_classification_problem

We'll be using the "mammographic masses" public dataset from the UCI repository (source: https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass)

This data contains 961 instances of masses detected in mammograms, and contains the following attributes:


   1. BI-RADS assessment: 1 to 5 (ordinal)  
   2. Age: patient's age in years (integer)
   3. Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
   4. Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
   5. Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)
   6. Severity: benign=0 or malignant=1 (binominal)
   
BI-RADS is an assesment of how confident the severity classification is; it is not a "predictive" attribute and so we will discard it. The age, shape, margin, and density attributes are the features that we will build our model with, and "severity" is the classification we will attempt to predict based on those attributes.

The assignment is part of a training for a machine learning certification:
## Your assignment

Apply several different supervised machine learning techniques to this data set, and see which one yields the highest accuracy. Apply:

* Decision tree
* Random forest
* KNN
* Logistic Regression
* XGBoost Classifier
* SVM
* Bagging Classifier
* AdaBoost Classifier

The main idea behind this exercise is to get a general methodology (this could be easily used in other classification problems) to choose the best classifier once the data is cleaned and ready to use.
