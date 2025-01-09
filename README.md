Hello ! 
This project aims to develop a predictive model to classify leads based on their likelihood of conversion using Logistic Regression and Decision Tree Classifier.
1. Data Cleaning:
Remove irrelevant features (e.g., unique identifiers) that do not contribute to the prediction process.
Standardize and normalize column names for consistency and compatibility.
Handle duplicate records to ensure the dataset's integrity.

3. Handling Missing Values:
Identify features with missing values.
Impute missing numerical data using the column's median to maintain data consistency.
Apply appropriate techniques for categorical variables (e.g., replacing missing values with the median or using indicator variables).

5. Splitting Data into Training and Testing Sets:
Divide the dataset into training (80%) and testing (20%) sets.
Use stratified sampling to maintain the proportion of the target variable in both splits.

7. Model Building:
Logistic Regression:
Train a logistic regression model to leverage its linear classification capabilities.
Interpret model coefficients to understand the impact of features on predictions.

Decision Tree Classifier:
Train a decision tree classifier to capture non-linear patterns and decision rules in the dataset.
Analyze the feature importance derived from the tree structure.

9. Model Evaluation:
Use the test dataset to evaluate both models.
Compute the following performance metrics for each model:
Accuracy Score: Measures the overall correctness of predictions.
Precision Score: Assesses how many predicted positive labels are correct.
Recall Score: Evaluates the model's ability to identify all actual positives.
F1 Score: Balances precision and recall for an overall performance metric.
Compare the models to determine which performs better based on the metrics.

