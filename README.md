# Credit_Risk_Analysis

## Overview

- In this Analysis, we are testing 6 different models to determine if any of them should be used in predicting credit card risk.

## Results

	### Naïve Random Oversampling
		
- 
- The Balanced Accuracy score for the Naive Random Oversampling model is 0.66. This means that the model is 66% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.01 meaning that model is unreliable on predicting true high credit risks.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.68 meaning that the model is mediocre at identifying high credit risk people.

### SMOTE Oversampling

- 
- The Balanced Accuracy score for the SMOTE Oversampling model is 0.65. This means that the model is 65% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.01 meaning that model is unreliable on predicting true high credit risks.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.61 meaning that the model is mediocre at identifying high credit risk people.


### Cluster Centroid Undersampling

- 
- The Balanced Accuracy score for the SMOTE Oversampling model is 0.54. This means that the model is 65% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.01 meaning that model is unreliable on predicting true high credit risks.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.69 meaning that the model is mediocre at identifying high credit risk people.


### SMOTEENN

- 
- The Balanced Accuracy score for the SMOTE Oversampling model is 0.67. This means that the model is 67% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.01 meaning that model is unreliable on predicting true high credit risks.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.74 meaning that the model is mediocre, but the best of the sampling methods at identifying high credit risk people.


### Balanced Random Forest Classifier

- 
- The Balanced Accuracy score for the SMOTE Oversampling model is 0.955. This means that the model is 95.5% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.06 meaning that model is unreliable on predicting true high credit risks, but higher than any of under/over sampling techniques.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 1.00 meaning that the model is “perfect” at identifying high credit risk people.


### Easy Ensemble AdaBoost

- 
- The Balanced Accuracy score for the SMOTE Oversampling model is 0.96. This means that the model is 96% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.11 meaning that model is still unreliable on predicting true high credit risks, but it is the best model for predicting a high credit risk.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.97 meaning that the model is near perfect at identifying high credit risk people.


## Summary

- I believe that if I was to use a model correctly identifying high credit risk people, I would use the Balanced Random Forest Classifier. It had a perfect score of identifying high credit risk people. There is not a model that has a better recall and the AdaBoost Classifier has a similar precision and F1 score meaning that the Balanced Random and AdaBoost were similarly reliable at predicting high credit risk people, and both Precision and Sensitivity were both similar. That is why I think in this case it would be best to use the Balanced Random Forest Classifier.

