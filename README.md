# Credit Risk Analysis with Machine Learning

## Overview

Supervised machine learning with Python was used to determine risk levels for credit. The data is used to determine who might be a high or low risk to recieve loans. Different methods of linear regression were used to determine the most accurate and least biased method.

## Results

### Naive Random Oversampling

- Balanced Accuracy Score: 0.647
- Precision Score: 0.01
- Recall Score: 0.69

![naive_sampling](https://user-images.githubusercontent.com/77767984/130332738-df10ac4b-3ced-47aa-9c66-03a3f3a973ff.PNG)

### SMOTE Oversampling

- Balanced Accuracy Score: 0.662
- Precision Score: 0.01
- Recall Score: 0.63

![smote_sampling](https://user-images.githubusercontent.com/77767984/130332792-6be34799-e775-4a0d-9ea3-96ba31d29430.PNG)

### Cluster Centroid Undersampling

- Balanced Accuracy Score: 0.544
- Precision Score: 0.01
- Recall Score: 0.69

![centroid_undersampling](https://user-images.githubusercontent.com/77767984/130332806-0f15947c-3f59-447c-8b9f-2d19b7d1019a.PNG)

### SMOTEENN Sampling

- Balanced Accuracy Score: 0.644
- Precision Score: 0.01
- Recall Score: 0.72

![SMOTEENN](https://user-images.githubusercontent.com/77767984/130332812-73b6f477-df4f-49c8-980d-15842e6b028a.PNG)

### Balanced Random Forest Classifier

- Balanced Accuracy Score: 0.7889
- Precision Score: 0.04
- Recall Score: 0.69

![randomforest](https://user-images.githubusercontent.com/77767984/130332827-6b2bc116-090b-4058-a726-9ecdf6ffa915.PNG)

### Easy Ensemble AdaBoost Classifying

- Balanced Accuracy Score: 0.9178
- Precision Score: 0.09
- Recall Score: 0.89

![easy_ensemble](https://user-images.githubusercontent.com/77767984/130332842-a7021fef-ddd7-4c37-8cd7-3f8692e8aafe.PNG)

## Summary

In conclusion, out of all the methods used, I would reccomend the Easy Ensemble method for determining who has a high credit risk and shouldn't be given a loan. It had the highest recall score at 89%, meaning that is the percentage of total high risk customers that were detected. However, although the precision score for this method was also the highest, it's still just below 10%, meaning less than 10% of all customers identified as being high credit risks actually were. This would bar legitimate customers with good credit from being able to be provided a loan.








