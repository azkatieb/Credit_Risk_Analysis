# Credit_Risk_Analysis

## Overview of the Analysis:
This analysis consisted of creating supervised machine learning models that could accurately predict the credit risk of the dataset provided.

The machine learning models that we used were: 
- Oversampling (RandomOverSampler)
- SMOTE Oversampler
- Undersampling (ClusterCentroids)
- Combination Over and Under Sampling (SMOTEENN)
- Balanced Random FOrest Classifier
- Easy Ensemble Classifier

## Results:

1. Oversampling

    Balanced Accuracy Score - 64.87%

    Precision Score - 0.98%

    Recall Score - 61%

![oversampling](/images/Oversampling%20Results.png)

2. SMOTE Oversampler

    Balanced Accuracy Score - 61.59%

    Precision Score - 0.83%

    Recall Score - 59%

![SMOTE](/images/SMOTE%20Oversampling.png)

3. Undersampling

    Balanced Accuracy Score - 51.7%

    Precision Score - 0.53%

    Recall Score - 64%

![undersampling](/images/Undersampling.png)

4. Combination Over and Undersampling

    Balanced Accuracy Score - 64.6%

    Precision Score - 0.87%

    Recall Score - 69%

![combination](/images/Combined%20Over%20and%20Under.png)

5. Balanced Random Forest Classifier

    Balanced Accuracy Score - 76.9%

    Precision Score - 2.75%

    Recall Score - 64%

![Balanc](/images/BalancedRandomForestClassifier.png)

6. Easy Ensemble Classifier

    Balanced Accuracy Score - 92.98%

    Precision Score - 6.27%%

    Recall Score - 92%

![easy ensemble](/images/Easy%20Ensemble%20Updated.png)

## Summary:

After using the six machine learning models above, it was found that the best model to predict the high risk loan applications out of all of the loan applications was the Easy Ensemble Classifier Model. The Easy Ensemble Classifier Model had an accuracy score of 92.98% where the other six models had anywhere from a 50-76% accuracy score so this model far and away was more accurate than the other models. 