# Credit_Risk_Analysis

## Overview

- In this Analysis, we are testing 6 different models to determine if any of them should be used in predicting credit card risk.

## Results

	### Naïve Random Oversampling
		
- ![image](https://user-images.githubusercontent.com/89875730/149418920-80f3afd3-df87-4d90-a6ea-f57dcf017a8d.png)

- The Balanced Accuracy score for the Naive Random Oversampling model is 0.66. This means that the model is 66% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.01 meaning that model is unreliable on predicting true high credit risks.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.68 meaning that the model is mediocre at identifying high credit risk people.

### SMOTE Oversampling

- ![image](https://user-images.githubusercontent.com/89875730/149418954-b37a5ad7-20d6-488d-a89f-0ba27dc17061.png)

- The Balanced Accuracy score for the SMOTE Oversampling model is 0.65. This means that the model is 65% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.01 meaning that model is unreliable on predicting true high credit risks.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.61 meaning that the model is mediocre at identifying high credit risk people.


### Cluster Centroid Undersampling

- ![image](https://user-images.githubusercontent.com/89875730/149418980-4e7c448d-d9ad-4cd3-910a-715d7304bcaa.png)

- The Balanced Accuracy score for the SMOTE Oversampling model is 0.54. This means that the model is 65% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.01 meaning that model is unreliable on predicting true high credit risks.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.69 meaning that the model is mediocre at identifying high credit risk people.


### SMOTEENN

- ![image](https://user-images.githubusercontent.com/89875730/149418991-00bdcdde-d3fc-4c8e-bea6-730c386f9f03.png)

- The Balanced Accuracy score for the SMOTE Oversampling model is 0.67. This means that the model is 67% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.01 meaning that model is unreliable on predicting true high credit risks.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.74 meaning that the model is mediocre, but the best of the sampling methods at identifying high credit risk people.


### Balanced Random Forest Classifier

- ![image](https://user-images.githubusercontent.com/89875730/149419008-6dcd0ff8-f76f-417b-af64-37e37d830890.png)

- The Balanced Accuracy score for the SMOTE Oversampling model is 0.955. This means that the model is 95.5% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.06 meaning that model is unreliable on predicting true high credit risks, but higher than any of under/over sampling techniques.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 1.00 meaning that the model is “perfect” at identifying high credit risk people.


### Easy Ensemble AdaBoost

- ![image](https://user-images.githubusercontent.com/89875730/149419036-606a1efe-0c45-494a-a806-1d8286e8ce2b.png)

- The Balanced Accuracy score for the SMOTE Oversampling model is 0.96. This means that the model is 96% accurate at predicting high credit risk.
- Precision for the Naïve Random Oversampling for high credit risk is 0.11 meaning that model is still unreliable on predicting true high credit risks, but it is the best model for predicting a high credit risk.
- Sensitivity for the Naïve Random Oversampling for high credit risk is 0.97 meaning that the model is near perfect at identifying high credit risk people.


## Summary

- I believe that if I was to use a model correctly identifying high credit risk people, I would use the Balanced Random Forest Classifier. It had a perfect score of identifying high credit risk people. There is not a model that has a better recall and the AdaBoost Classifier has a similar precision and F1 score meaning that the Balanced Random and AdaBoost were similarly reliable at predicting high credit risk people, and both Precision and Sensitivity were both similar. That is why I think in this case it would be best to use the Balanced Random Forest Classifier.

