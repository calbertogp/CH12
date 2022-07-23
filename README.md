# CH12
Carlos A. Guerra

Tech: Python, Pandas, Numpy, sklearn.metrics(balances_accuracy_score, confusion matrix, classification_report_imbalanced), sklearn.model_selection (train_test_split), sklearn.linear_model(LogisticRegression), sklearn.metrics(accuracy_score), imblearn.over_sampling (RandomOverSampler) 


Module 12 Report Template
Overview of the Analysis
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

Explain the purpose of the analysis.
Explain what financial information the data was on, and what you needed to predict.
Provide basic information about the variables you were trying to predict (e.g., value_counts).
Describe the stages of the machine learning process you went through as part of this analysis.
Briefly touch on any methods you used (e.g., LogisticRegression, or any resampling method).
Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1: In this model I was trying to predict risky loan applications so that they can be flagged while in the application process.
Machine Learning Model 2: Same but with Random over fitting.
Description of Models and diferences between 2nd and first: Recall for true-negatives increase 0.08 to .99 and false-positives decreases by .01 to 0.84. Accuracy also improved slightly to 0.9939 from 0.9918.
Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Which one seems to perform best? How do you know it performs best?
The second one with ROS increased 0.08 in true-negatives
Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's? ) Yes, depending on the problem the 1 or 0 will have a different monetary value and importance tied to it.


Columbia
