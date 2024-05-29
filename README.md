# PRODIGY_DS_03
Task 3:
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.


The project involved the analysis and prediction of whether a bank customer will subscribe to a term deposit. Using the provided dataset, various data preprocessing steps, exploratory data analysis, and a machine learning model were implemented.

Data Preprocessing and Cleaning:

>The dataset was loaded and inspected for null values and duplicates.

>Categorical variables were identified and encoded into numerical values using Label Encoding.

>Outliers in numerical columns such as 'age', 'campaign', and 'duration' were handled using the IQR method.

>Highly correlated features (correlation ≥ 0.90) such as 'emp.var.rate', 'euribor3m', and 'nr.employed' were removed to avoid multicollinearity issues.


Exploratory Data Analysis (EDA):

>Visualizations were created to understand the distribution of numerical and categorical features.

>Histograms, boxplots, and count plots provided insights into the data distribution and potential patterns.

>The correlation matrix and heatmap were used to identify highly correlated features.


Model Building and Evaluation:

>The Decision Tree Classifier was chosen for the prediction task.

>The dataset was split into training and testing sets with a 75-25 ratio.

>The model achieved a training accuracy of 96.3% and a testing accuracy of 94.4%.

>The model's performance was evaluated using accuracy score, confusion matrix, and classification report:

>Accuracy Score: 94.4%

>Confusion Matrix: Indicated a high number of true positives and negatives, but some misclassifications.

>Classification Report: Highlighted that the model performed well with high precision and recall for the majority class (no deposit), but the performance was lower for the minority class (yes deposit).

Decision Tree Visualization:
The decision tree model was visualized to understand the decision rules and the importance of features.
