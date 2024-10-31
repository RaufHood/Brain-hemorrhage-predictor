# Inroduction
The goal of this project is to assess the risk of developing a brain hemorrhage in preterm childreen.
This project is inspired by the research paper: Machine learning models for identifying preterm infants at risk of cerebral hemorrhage.

# Dataset
The dataset used contains 316 patients, and dozens of datapoints for each patient including (such as apgar score, hematocrit, weight, CO2 partial pressure ..)

# Methods
1.  Exploratory data Analysis is performed.  
2. features engineering is performed, where the average min and maximum values of relevant features are calculated.  
3. Feature selection is applied, to retain only relevant features.  
4. Several classification algorithms were tested and compared, including xgboost, random forest, logistic regression and SVM.
5. Fine tuning and evalution on the test set.

# Conclusion
This project shows promising results in the prediction of risk assessment of brain hemorrhage in preterm infants. 
However, the collection of a larger dataset is required to achieve better performance.
