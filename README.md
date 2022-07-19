# Credit Risk Analysis: Supervised Machine Learning


## Purpose of Review

Credit risk has the issue of having far more good loans when compared to risky loans. This creates an unbalanaced clasification problem when it comes to evaulating credit risk in a large data set. To help aid in the review of credit risk I have been asked to use two machine learning libraries to review the data set and use Supervised Machine Learning techniques to have engaging data that can be used to predict the credit risk in the mortgage data set.

**Libraries Used:**
  - imbalanced-learn
  - scikit-learn
  
**Types of Machine Learning Techniques Used:**
  1) Random Over Sampling
  2) SMOTE
  3) Cluster Centroids
  4) SMOTEENN
  5) Balanced Random Forest Classifer
  6) Easy Ensemble Classifier
  
## Supervised Machine Learning Results

### Random Over Sampling

![ros_report](https://user-images.githubusercontent.com/100856534/179804637-f4c21890-9a4a-45f6-9bc7-833a4ea40261.png)

- Balanced Accuracy Score: 64.1%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 60%-High_Risk and 68%-Low_Risk

### SMOTE
  
![SMOTE](https://user-images.githubusercontent.com/100856534/179806271-c5b45f9e-1c0f-476c-89c8-70964f34e758.png)

- Balanced Accuracy Score: 63.7%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 60%-High_Risk and 68%-Low_Risk

### Cluster Centroids

![ClusterCentroids](https://user-images.githubusercontent.com/100856534/179806614-dcb000fb-16a1-4945-aa4d-d7d04b4fc21b.png)

- Balanced Accuracy Score: 63.7%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 61%-High_Risk and 45%-Low_Risk

### SMOTEENN

![SMOTEENN](https://user-images.githubusercontent.com/100856534/179806972-623bf5a3-8b79-4753-adff-f2d2d0267dc1.png)

- Balanced Accuracy Score: 52.9%
- Precision Scores show that it is low for High_Risk (.01) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 70%-High_Risk and 57%-Low_Risk

### Balanced Random Forest Classifer

![BalForest](https://user-images.githubusercontent.com/100856534/179807235-3c60ea09-88c0-4cb0-9fb8-f2c207a879d7.png)

- Balanced Accuracy Score: 78.9%
- Precision Scores show that it is low for High_Risk (.03) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 70%-High_Risk and 87%-Low_Risk

### Easy Ensemble Classifier

![Easy](https://user-images.githubusercontent.com/100856534/179807495-30b5f0d8-e880-454d-a0dd-9b5bdfb5a1a6.png)

- Balanced Accuracy Score: 93.2%
- Precision Scores show that it is low for High_Risk (.09) and very high for Low_Risk (1.0) for credit risk assessments
- Recall Scores: 92%-High_Risk and 94%-Low_Risk

## Summary

With each of the methods used the balanced accuracy ranged from 52.9%, with SMOTEENN, to 93.2%, with Easy Ensamble Classifier. For most of the precisions scores they remained for a majority of the techinques at .01 for High_Risk and 1.00 for Low_Risk. The only risk level that moved was for High_Risk. Other others were at .01 except for Balanced Random Forest Classifer, which was at .03, and Easy Ensemble Classifer, which was at .09. The recall rates were different for each group as well. The highest recall rate for High_Risk was Easy Ensemble at 92%. The highest recall rate for Low_Risk was also the Easy Ensemble at 94%. 

With reviewing all of the methods above the Easy Ensemble Classifier gives the best results in all three catagories reviewed, Balanced Accurary, Precision, and Recall. I would move forward with Easy Ensemble for future machine learning objectives. 
