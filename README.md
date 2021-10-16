# HW17 Credit Risk Analysis

## Overview of Analysis
* ####  Our credit risk data will be analyzed using 6 methods to determine which machine learning model has the best result in predicting outcomes of loans.

## Results
<pre>
 Algorithm Name                     | Balanced  | Precision | Recall |
                                    | Accuracy  |           |        |
|-----------------------------------|-----------|-----------|--------|
<span>&#8226;</span> RandomOverSampler                 |   57.3%   |     99%   |   71%  |
<span>&#8226;</span> SMOTE                             |   64.8%   |     99%   |   74%  |
<span>&#8226;</span> ClusterCentroids                  |   53.8%   |     99%   |   53%  |
<span>&#8226;</span> SMOTEENN                          |   65.6%   |     99%   |   58%  |
<span>&#8226;</span> BalancedRandomForestClassifier    |   81.1%   |     99%   |   89%  |
<span>&#8226;</span> EasyEnsembleClassifier            |   92.4%   |     99%   |   94%  |</pre>

* #### RandomOverSampler


