# Credit_Risk_Analysis
## Overview:
Creating machine learning model to predict credit risk from a credit card credit dataset. The data needs to be oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. Then a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Then compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results:
* RandomOverSampler - oversampling<br/>
![1_Random_Over_Sampler](https://user-images.githubusercontent.com/85530486/141718508-efd4aae5-c231-4893-b568-33674a92db83.png)

* SMOTE - oversampling<br/>
![2_SMOTE_Oversampling](https://user-images.githubusercontent.com/85530486/141718569-bddb7126-35bb-4b62-86a3-df488148a98c.png)

* ClusterCentroids - undersampling<br/>
![3_Cluster_Centroid_Undersampling](https://user-images.githubusercontent.com/85530486/141718656-96affcf5-a74e-4637-b7c9-d30dd61e7391.png)

* SMOTEENN - combination<br/>
![4_SMOTEENN_Combination](https://user-images.githubusercontent.com/85530486/141718762-6b152079-9f0c-4004-9eb3-22cb2e1f5936.png)

* Random Forest Classifying<br/>
![5_Random_Forest_Classifying](https://user-images.githubusercontent.com/85530486/141718842-62647430-77eb-463a-bd73-67708b6129c1.png)

* Easy Ensemble Classifying<br/>
![6_Easy_Ensemble_Classifying](https://user-images.githubusercontent.com/85530486/141718874-5881dec7-9cd5-46ed-a4be-4a640cfcf8f5.png)

## Summary:
Out of all the models Random Forest Classifying and Easy Ensemble Classifying models performed better than all others returning 100% score for - average precision, average recall (sensitivity) and average F1 score. 

The recommendation would be to use Easy Ensmble model as it returned higher accuracy score. 
