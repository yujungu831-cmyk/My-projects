# Fraud Detection

**Target:**
Develop machine learning models using Python to predict fraudulent transactions and analyze the predicted results

**Data source:**
Simulated dataset

**required python module**

- numpy
- pandas
- matplotlib
- seaborn 
- sklearn
- imblearn *(Install directly during code execution)*
- time

**Methods:**

- Import data
- Data exploration
- Feature engineering
- Data split
- Model Training(including Logistic Regression, Random Forest and SMOTE)
- GridSearchCV
- Result Evaluation 

**Main steps:**

 1. import data and analyze it with ``pandas_profiling.ProfileReport()``
 2. Predict the potential impact of data on the results
 3. Identify country info based on ip_address
 4. deal with time-dependent variables
 5. drop useless data and split it
 6. encode data
 7. standardize data
 8. build models and train them
 9. compare three models and find the best one
 10. find the better parameters
 11. compare the feature importance
 12. apply in practice


**Key conclusion:**

 - Random Forest performed the best in this project.
 - The most influential factors are time and n_dev_shared.
