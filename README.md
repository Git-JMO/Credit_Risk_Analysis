# Credit_Risk_Analysis
## Overview 
   * The purpose of this analysis was to accurately predict credit risk based on loan data from the year 2019. In order to accomplish this assignment, multiple supervised machine learning models were created along with a variety of sampling techniques.
   * For this assignment, we tested one naive oversampling algorithm and one SMOTE algorithm, one undersampling algorithm, a combination algorithm, and 2 ensemble algorithms (this entailed a Balanced Random Forest Classifier and an Easy Ensemble AdaBoost Classifier)

## Results:
   * Naive Oversampling ALgorithm
     * Accuracy Score: 0.62
     * Precision Score: 0.99
     * Recall Score: 0.63
   * SMOTE Algorithm
     * Accuracy Score: 0.62
     * Precision Score: 0.99
     * Recall Score: 0.65
   * Undersampling Algorithm
     * Accuracy Score: 0.62
     * Precision Score: 0.99
     * Recall Score: 0.57
   * Combination Algorithm
     * Accuracy Score: 0.54
     * Precision Score: 0.99
     * Recall Score: 0.58
   * Balanced Random Forest Classifier
     * Accuracy Score: 0.92
     * Precision Score: 0.99
     * Recall Score: 0.92
   * Easy Ensemble AdaBoost Classifier
     * Accuracy Score: 0.94
     * Precision Score: 0.99
     * Recall Score: 0.94

## Summary:
   * After reviewing and analyzing the results, it is evident the ensemble models have a higher accuracy than the other four models. Furthermore, the precision scores associated with all six models faired well; however, there is more variety amongst the recall scores. Therefore, it can be determined that those who are deemed a high risk are most likely to actually be high risk. However, ultimately the ensemble models are more reliable in determining those who are high risk. I would highly recommend leveraging the ensemble models as they are more reliable in correctly flagging high risk applicants.
