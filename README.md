# CardiacArrest
# Conclusion:
### 1.The DataSet had a lot of missing values in one of the categorical variables smoking status and a continuous variable BMI . We Conducted  a chi square test for independence to check if the missingness in BMI is in anyway related to the missingness in smoking status which indeed was the case and hence we used MICE imputation technique to impute the missing values. The missing values in the case of smoking status were then rounded off to nearest integral values. 
### 2. A slight distortion of distribution and varianc ewas onserved in this imputation.
### 3. EDA was performed to check if there was any relationship amongst variables which indeed was the case thus giving idea that Logistic Regression would be the best for the prediction of model.
### 4. The logistic Regression initially gave an accuracy of 95% which then was improved by discarding various less corelated features and the improved accuracy shooted up to 98%
### 5. Various other techniques like Decision trees, RandomForest and KNN classification were also used and then accuracy was tested using k folds cross validation tests. 
### 6. In case of KNN Imputation, elbow method and cross val score was used to determine the optimum k which came out to be 12 and the accuracy was as good as Logistic Regression.
### 7. EDA gave a huge evidence that marriage, work type and high BMI cause Hypertension
### 8. We also conclude that Males are more prone to high BMI and high risk of hypertension and stroke than females
### 9. The model was then dumped using Joblib
