# HW17 Credit Risk Analysis

## Overview of Analysis
* ####  Our credit risk data will be analyzed using 6 methods to determine which machine learning model has the best result in predicting outcomes of loans.

## Results
<pre>
        Algorithm Name              | 
        Balanced  | Precision | Recall |
                                    | Accuracy  |           |        |
|-----------------------------------|-----------|-----------|--------|
<span>&#8226;</span> RandomOverSampler                 |   64.9%   |     99%   |   57%  |
<span>&#8226;</span> SMOTE                             |   65.8%   |     99%   |   68%  |
<span>&#8226;</span> ClusterCentroids                  |   54.4%   |     99%   |   40%  |
<span>&#8226;</span> SMOTEENN                          |   66.2%   |     99%   |   54%  |
<span>&#8226;</span> BalancedRandomForestClassifier    |   78.5%   |     99%   |   90%  |
<span>&#8226;</span> EasyEnsembleClassifier            |   91.3%   |     99%   |   95%  |</pre>

*  RandomOverSampler
   *  RandomOverSampler produced an accuracy of 64.9%.
  
![](https://github.com/ethiry99/HW17_Credit_Risk_Analysis/blob/main/Resources/Images/ROS.PNG?raw=true)
*  SMOTE
   *  SMOTE produced an accuracy of 65.8%.  A little better but not significantly so. 
  
 ![](https://github.com/ethiry99/HW17_Credit_Risk_Analysis/blob/main/Resources/Images/SMOTE.PNG?raw=true) 
*  ClusterCentroids
   *  ClusterCentroids produced an accuracy of 54.4%.  The accuracy dropped with this method, lets see if we can move the score back up!
  
![](https://github.com/ethiry99/HW17_Credit_Risk_Analysis/blob/main/Resources/Images/CC.PNG?raw=true)
*  Smoteenn
   *  SMOTEENN produced an accuracy of 66.2%.  The best score so far! Let's see if the ensemble methods can out perform what we have so far.
  
![](https://github.com/ethiry99/HW17_Credit_Risk_Analysis/blob/main/Resources/Images/SMOTEENN.PNG?raw=true)
*  BalancedRandomForestClassifier
   *  BalancedRandomForestClassifier came in with an accuracy of 78.5%. By far the best so far.  
  
![](https://github.com/ethiry99/HW17_Credit_Risk_Analysis/blob/main/Resources/Images/BRFC.PNG?raw=true)

*  EasyEnsembleClassifier
   *  EasyEnsembleClassifier has an accuracy of 91.3%. A clear winner.
  
![](https://github.com/ethiry99/HW17_Credit_Risk_Analysis/blob/main/Resources/Images/Easy.PNG?raw=true)
## Summary 
As can be seen in the table and brief review of the results the method with the highest accuracy was EasyEnsembleClassifier.  With the clear advantage that this method has in the given data sample, it is recommended to utilize it in when determine loan risk.
  

