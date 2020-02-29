# Supervised_Machine_Learning

Assesing credit risk by using different techniquest ot train and evalute a model the unbalanced classification problem, as the number of good loans outnumber the number of risky loans. With the use of imbalanced-learn and scikit-learn libraries a model is built for resampling. Your final task is to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

Based on the sampling methods used, it would be the best to use Easy Ensemble classifier as it provided with the highest precision and recall socres.

Below are the results of the various sampling methods applied to the dataset. 

### Random Oversampling CLassification Report: 
- A very high precision score (0.99) compared to the recall score (0.63)
- Balanced accuracy score of .65

![Random_Oversampling](https://github.com/Wish-Patel/Supervised_Machine_Learning/blob/master/Random_Oversampling.PNG)


### SMOTE Oversampling CLassification Report:
- A very high precision score (0.99) compared to the recall score (0.69)
- Balanced accuracy score of .66
![SMOTE_Oversampling](https://github.com/Wish-Patel/Supervised_Machine_Learning/blob/master/SMOTE_Oversampling.PNG)


### Undersampling CLassification Report:
- A very high precision score (0.99) compared to the recall score (0.55)
- Balanced accuracy score of .58
![Undersampling](https://github.com/Wish-Patel/Supervised_Machine_Learning/blob/master/Undersampling.PNG)


### Combination Sampling CLassification Report:
- A very high precision score (0.99) compared to the recall score (0.55)
- Balanced accuracy score of .58
![CombinationSampling](https://github.com/Wish-Patel/Supervised_Machine_Learning/blob/master/CombinationSampling.PNG)


### Balance Random Forest CLassification Report:
- A very high precision score (1.00) compared to the recall score (1.00)
- Balanced accuracy score of .68
![BalancedRandomForest](https://github.com/Wish-Patel/Supervised_Machine_Learning/blob/master/BalancedRandomForest.PNG)


### Easy Ensemble AdaBoost CLassification Report:
- A very high precision score (0.99) compared to the recall score (0.94)
- Balanced accuracy score of .93
![Combination Sampling](https://github.com/Wish-Patel/Supervised_Machine_Learning/blob/master/EasyEnsembleAdaBoost.PNG)
