# Credit Risk Analysis

### Purpose
Since credit risk is an unbalanced classification issue as good loans easily outnumber risky loans, various machine learning models to predict risk need to be evaluated to determine the best one to use.

## Analysis

### Results

Six different machine learning models were tested to predict credit risk.  Below are the accuracy, precision, and recall scores of all models.


1)	Naïve Random Oversampling

![naive oversampling](https://user-images.githubusercontent.com/80165223/125173236-e5f5f900-e183-11eb-906e-7ccff88550fe.png)



2)	SMOTE Oversampling


![SMOTE](https://user-images.githubusercontent.com/80165223/125173238-e9898000-e183-11eb-9c77-02b2127cf857.png)



3)	Undersampling


![Undersampling](https://user-images.githubusercontent.com/80165223/125173242-eee6ca80-e183-11eb-9133-37019b41ba7b.png)



4)	Combination


![Combination](https://user-images.githubusercontent.com/80165223/125173248-f312e800-e183-11eb-9211-b3f237e4511f.png)



5)	Random Forest

![Random Forest](https://user-images.githubusercontent.com/80165223/125173254-f60dd880-e183-11eb-8857-a89a6d5bb150.png)



6)	Easy Ensemble Adaboost


![AdaBoost](https://user-images.githubusercontent.com/80165223/125173265-002fd700-e184-11eb-8086-ab012bfaa4bc.png)



## Summary

In general, the ideal model would be both precise and sensitive; however, that is not the case with any of the models in this analysis.  Given that a customer service representative can have a verbal conversation with an applicant to further detail out the variables that drive credit risk, high sensitivity in a model is the priority as false negatives for high risk would pose a significant challenge for a company.  False positives are ideal over false negatives.

In all models except for the AdaBoost model sensitivity for detecting high risk is well below 5%.  The sensitivity for predicting high risk individuals is over 90% in the AdaBoost model and the accuracy is at 92%; therefore, it is the recommended model for predicting credit risk.
