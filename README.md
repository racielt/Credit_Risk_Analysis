# Credit_Risk_Analysis


## Overview
The purpose of this analysis is to help Jill to predict credit risk. 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. 

We used the credit card credit dataset from LendingClub and different models and algorithms to analyzed it. 

Also we are evaluating the performance of these models.

## Results

- Naive Random Oversampling

The balanced accuracy obtained was 65%, the precision for the high_risk is at 1% and the recall is 72%

<img width="646" alt="Screen Shot 2022-01-31 at 10 07 32" src="https://user-images.githubusercontent.com/90534703/151823433-eab7c903-0417-4018-9acf-8a85a5f9de55.png">


- SMOTE Oversampling

The balanced accuracy obtained was 66%, the precision for the high_risk is at 1% and the recall is 63%

<img width="646" alt="Screen Shot 2022-01-31 at 10 13 39" src="https://user-images.githubusercontent.com/90534703/151823457-e834672d-22ed-4c4d-aa12-6741260ef6d7.png">


- Undersampling

The balanced accuracy obtained was 54%, the precision for the high_risk is at 1% and the recall is 69%

<img width="645" alt="Screen Shot 2022-01-31 at 10 14 26" src="https://user-images.githubusercontent.com/90534703/151823469-489d4cd9-6407-45ac-b92e-ad590e05cc7c.png">


- Combination (Over and Under) Sampling

The balanced accuracy obtained was 65%, the precision for the high_risk is at 1% and the recall is 72%

<img width="655" alt="Screen Shot 2022-01-31 at 10 15 07" src="https://user-images.githubusercontent.com/90534703/151823483-182fca1f-47a9-421f-ab4e-50747f90e557.png">


- Balanced Random Forest Classification

The balanced accuracy obtained was 77%, the precision for the high_risk is at 3% and the recall is 65%

<img width="652" alt="Screen Shot 2022-01-31 at 10 32 40" src="https://user-images.githubusercontent.com/90534703/151823500-7b6b64b1-fc68-4240-b4ea-77a8e97e5ead.png">


- Easy Ensemble AdaBoost Classifier

The balanced accuracy obtained was 93%, the precision for the high_risk is at 9% and the recall is 92%

<img width="641" alt="Screen Shot 2022-01-31 at 10 34 38" src="https://user-images.githubusercontent.com/90534703/151823555-759c0351-4ef9-475a-96e6-a9fe912708cc.png">



## Summary

As we can see the best model we have is the Easy Ensemble Classifier, with an accuracy rate of 93% and a 9% precision rate predicting High Risk candidates, and with a recall of 92%.
Regarding low risk rates, this model also get the best results of all of them.

After running these six models, we can decided to go with Easy Ensemble, thanks to the results previously mentioned.






