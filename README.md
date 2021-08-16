# Credit_Risk_Analysis

## Overview: 
Six supervised machine learning models were built and evaluated to determine which, if any model, could be implemented to better determine an applicant's credit risk. 

## Results:

* **Balanced Random Forest Classifier**

![BRFC.PNG](https://github.com/worksm/Credit_Risk_Analysis/blob/c4d10834c7c38c8ebbd8c70c776583caeb3f06fa/BRFC.png)

* **Easy Ensemble AdaBoost Classifer**

![EEAB1.PNG](https://github.com/worksm/Credit_Risk_Analysis/blob/0dcc589c0ea58093a401a67e58bc9394a7f9ec0e/EEAB1.png)

  * Both ensemble models have the highest accuracy score at 76%. 
  * Both models are able to predict the low risk borrowers with 100% precision, 90% recall, and high risk borrowers 4% precision, 62% recall.  


* **Naive Random Oversampling**

  * This model accuracy score is 66%. 
  * Both models are able to predict the low risk borrowers with 100% precision, 61% recall, and high risk borrowers 1% precision, 70% recall.  

![Naive_Oversampling](https://github.com/worksm/Credit_Risk_Analysis/blob/0bcde69fd16efff1b82314cbb8b2bde6bce930e1/Naive_Oversampling.png)


* **Smote Oversampling**

 * This model accuracy score is 66%. 
 * Both models are able to predict the low risk borrowers with 100% precision, 57% recall, and high risk borrowers 1% precision, 64% recall.  

![Smote_Oversampling](https://github.com/worksm/Credit_Risk_Analysis/blob/0bcde69fd16efff1b82314cbb8b2bde6bce930e1/Smote_Oversampling.png)

* **Undersampling**

 * This model accuracy score is 66%. 
 * Both models are able to predict the low risk borrowers with 100% precision, 69% recall, and high risk borrowers 1% precision, 63% recall.  

![Undersampling](https://github.com/worksm/Credit_Risk_Analysis/blob/6051b229c8827ed59cffd9b3704c861d84933b94/Undersampling.png)

* **Combination**


  * This model accuracy score is 61%. 
  * Both models are able to predict the low risk borrowers with 100% precision, 57% recall, and high risk borrowers 1% precision, 72% recall.  

![Combo](https://github.com/worksm/Credit_Risk_Analysis/blob/0bcde69fd16efff1b82314cbb8b2bde6bce930e1/Combo.png)

## Summary: 

In summary, I would be unable to recommend any of the machine learning models in their current state. The highest accuracy score for any model was 76%, the highest recall score was 90% among low risk borrowers. The highest recall score for high risk borrowers, the most important group to identify, is 72%. The best course of action at this time would be to evaluate and revise some of the highest performing models, Combo, Naive Random Oversampling, and Balanced Random Forest Classifer and work towards improving the recall scores for high risk borrowers. 
