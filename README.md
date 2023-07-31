-# credit-risk-classification
Overview of the Analysis:

The purpose of this analysis was to build and evaluate machine learning models to predict a binary outcome based on financial information. The data provided contained various financial features, and we needed to predict whether a given loan application would result in a default (1) or not (0).

The variables we were trying to predict were the loan status, which could be either "0" (non-default) or "1" (default). We used various machine learning models to predict this binary outcome.

The stages of the machine learning process we went through as part of this analysis include:

1. Data Preprocessing: We cleaned and prepared the data, handling missing values, encoding categorical variables, and scaling numerical features using StandardScaler.

2. Model Training and Evaluation: We trained several machine learning models, including Logistic Regression, Random Forest Classifier, and Support Vector Classifier, to predict loan defaults. We used cross-validation to evaluate each model's performance and prevent overfitting.

3. Resampling: As the dataset was imbalanced with a higher number of non-defaults compared to defaults, we employed resampling techniques such as RandomOverSampler to balance the classes and improve model performance.

Results:

Machine Learning Model 1:

0: Precision: 1.00, Recall: 1.00, balanced accuracy score: 0.944, f1-score: 1.00

1: Precision: 0.87, Recall: 0.89, balanced accuracy score: 0.944, f1-score: 0.88

Machine Learning Model 2:

0: Precision: 0.99, Recall: 0.99, balanced accuracy score: 0.994, f1-score: 0.99

1: Precision: 0.99, Recall: 0.99, balanced accuracy score: 0.994, f1-score: 0.99

Summary:

Based on the results, Model 2 performed better than Model 1 with the highest balanced accuracy score, precision, and recall. We determined this by comparing the metrics obtained for each model during the evaluation.

Performance might depend on the problem we are trying to solve. For example, if it is more critical to correctly predict loan defaults, then maximizing the recall score would be crucial to identify as many defaults as possible, even if it increases false positives. On the other hand, if predicting non-defaults is more important, maximizing precision would be a priority to reduce false positives.

Overall, Model 2 is recommended due to its superior performance in predicting loan defaults. However, the decision ultimately depends on the specific goals and priorities of the business or application. If the balance between recall and precision is crucial, further fine-tuning of the models might be necessary. Additionally, collecting more data or experimenting with different features could potentially improve model performance further.
