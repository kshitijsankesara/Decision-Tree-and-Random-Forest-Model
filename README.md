# Decision-Tree-and-Random-Forest-Model

I worked on an Employee Attrition model that can help organizations attract and retain top talent. I determined the factors that keep employees working at a company and which prompt them to leave the company. Understanding the factors is very important for HRs. The data contains various information about the past and current employees. The important task is to understand how each variable affects the workforce attrition. I developed decision tree and random forest model to classify employees using the significant variables.

**Data Exploration:**
1. Checking data types
2. Describing the numerical variables
3. Dropping variables that are not significant
4. Building histograms to understand distribution of the data

**Data Processing:**
1. Creating list of categorical variables
2. Performing Label Encoding on categorical variables to convert them
3. Seperating independent and dependent variables

**Decision Tree:**
1. Fitting decision tree model using DecisionTreeClassifier
2. Improved model by performing hyperparameter tuning
3. Parameters Used:
* Criterion
* Splitter
* Max_Depth
* Minimum_Sample_split
* Minimum_Samples_Leaf
4. Evaluated model using multiple metrics like Accuracy, Classification Report, Confusion Matrix

**Random Forest:**
1. Fitting the random forest model using RandomForestClassifier
2. Changing n_estimators to improve the model
3. Performed hyperparameter tuning
4. Evaluate model using different evaluation metrics
