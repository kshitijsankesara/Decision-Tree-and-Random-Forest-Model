# Decision-Tree-and-Random-Forest-Model

I worked on an Employee Attrition model that can help organizations attract and retain top talent. I determined the factors that keep employees working at a company and which prompt them to leave the company. Understanding the factors is very important for HRs. The data contains various information about the past and current employees. The important task is to understand how each variable affects the workforce attrition. I developed decision tree and random forest model to classify employees using the significant variables.

**Data Exploration:**
Checking data types
Describing the numerical variables
Dropping variables that are not significant
Building histograms to understand distribution of the data

**Data Processing:**
Creating list of categorical variables
Performing Label Encoding on categorical variables to convert them
Seperating independent and dependent variables

**Decision Tree:**
Fitting decision tree model using DecisionTreeClassifier
Improved model by performing hyperparameter tuning
Parameters Used - Criterion
Splitter
Max_Depth
Minimum_Sample_split
Minimum_Samples_Leaf
Evaluated model using multiple metrics like
Accuracy
Classification Report
Confusion Matrix

**Random Forest:**
Fitting the random forest model using RandomForestClassifier
Changing n_estimators to improve the model
Performed hyperparameter tuning
Evaluate model using different evaluation metrics
