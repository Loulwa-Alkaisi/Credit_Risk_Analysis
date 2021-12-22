# ***Credit Risk Analysis***
## **Overview:**
The main purpose of this analysis is to predict the credit risk using supervised machine learning model. For this analysis we used the following methods to split the data into testing and training data, then we looked at the accuracy scores, confusion matrix, and classification reports:
**a-** Naive Random Oversampling
**b-** SMOTE Oversampling
**c-** Cluster Centroid Undersampling
**d-** SMOTEENN Sampling
**e-** Balanced Random Forest Classifying
**f-** Easy Ensemble Classifying.

## **Results:**

### Naive Random Oversampling
![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/AS_NaiveOS.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/cm_NaiveOS.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/CR_NaiveOS.png)

Based on this model we can see that the naive random oversampling accuracy score is **64.97%**, the percision high risk is equal to **1%**, and the recall high risk is equal to **62%**. On the other hand, the low risk percision is **100%**, and the low risk recall is **68%**.

## SMOTE Oversampling
![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/AS_SMOTE.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/cm_SMOTE.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/CR_SMOTE.png)

Based on this model we can see that the SMOTE oversampling accuracy score is **64.43%**, the percision high risk is equal to **1%**, and the recall high risk is equal to **63%**. On the other hand, the low risk percision is **100%**, and the low risk recall is **66%**.

### Cluster Centroid Undersampling
![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/AS_CC.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/cm_CC.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/CR_CC.png)

Based on this model we can see that the cluster centroid undersampling accuracy score is **52.3%**, the percision high risk is equal to **1%**, and the recall high risk is equal to **61%**. On the other hand, the low risk percision is **100%**, and the low risk recall is **45%**.

### SMOTEENN Sampling
![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/AS_SMOTEENN.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/cm_SMOTEENN.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/CR_SMOTEENN.png)

Based on this model we can see that the SMOTEENN sampling accuracy score is **62.45%**, the percision high risk is equal to **1%**, and the recall high risk is equal to **68%**. On the other hand, the low risk percision is **100%**, and the low risk recall is **57%**.

### Balanced Random Forest Classifying
![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/AC_BRFC.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/cm_BRFC.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/CR_BRFC.png)

Based on this model we can see that the balanced random forest classifying accuracy score is **78.77%**, the percision high risk is equal to **4%**, and the recall high risk is equal to **67%**. On the other hand, the low risk percision is **100%**, and the low risk recall is **91%**.

### Easy Ensemble Classifying
![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/AC_EE.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/cm_EE.png)

![image](https://github.com/Loulwa-Alkaisi/Credit_Risk_Analysis/blob/6a46394575d3c4951c2fc59871049a44736b44cd/images/CR_EE.png)

Based on this model we can see that the easy ensemble classifying accuracy score is **68.9%**, the percision high risk is equal to **85%**, and the recall high risk is equal to **38%**. On the other hand, the low risk percision is **100%**, and the low risk recall is **100%**.


## **Summary:**
All the resampling models shows a very low percision in determining if a credit is high risk. On the other hand, in the ensemble model we can see those number increase, especially in the easy ensemble classifying model where it shows a high risk percision og 85% with an accuracy score of 68%. Given these results, I think the easy ensemble classifier might be the best optuion to be looked at.