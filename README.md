                                               Churn Customer Prediction - Machine Learning  
                                                             
                                                         
**Overview**

This GitHub repository contains a comprehensive machine-learning project for predicting bank customer churn. Churn prediction is crucial for businesses to identify customers who are likely to leave, allowing proactive measures to retain them.
The project utilizes various algorithms and techniques to analyze and predict customer behavior.

____________________________________________VARIABLE DESCRIPTIONS OF DATAFRAME BANK CUSTOMER CHURN PREDICTION____________________________________________

**CustomerId**: Each Customer contains a unique customer ID

**Credit Score**: A credit score is primarily based on a credit report, information typically sourced from credit bureaus.

**COUNTRY** : France ; Germany ; Spain

**GENDER** : Male ; Female

**AGE** 

**TENURE**: Customer maintains a relationship with the bank for how many years.

**BALANCE**: Customer's average bank balance.

**PRODUCTS NUMBER**: Number of product's customer

**CREDIT CARD** : Active & Inactive credit card customer.

**ACTIVE MEMBER** : Active & Inactive customer holding products.

**ESTIMATED SALARY**: Estimated salary of customer.

**CHURN (0 = No; 1 = Yes)**: Customer who stops using product or service over a defined period. 



                                            It includes the following key features
                                            
**Data Exploration**: The project begins with exploring and understanding the dataset, checking for null values, and visualizing the data distribution.

**Data Preprocessing**: The dataset undergoes preprocessing steps, such as handling categorical variables using Label Encoding and addressing data imbalances.

**Modeling**: Different machine learning models, including Logistic Regression, Decision Trees, Random Forest, AdaBoost, Gradient Boosting, and XGBoost, are applied to predict customer churn.

**Evaluation**: Model performance is evaluated using metrics such as precision, recall, and F1-score. Various pruning techniques are applied to enhance model accuracy and reduce overfitting.

**Conclusion**: The project concludes with a detailed analysis of the best-performing algorithms on the given dataset. AdaBoostClassifier, GradientBoostingClassifier, and XGBClassifier emerge as the most effective models for predicting customer churn.
