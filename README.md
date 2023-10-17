# Lead-Score-Case_Study
Building a logistic regression ML model to see which model can give the efficient results
X Education, a provider of online courses for professionals, is seeking assistance in identifying the leads with the highest potential for conversion into paying customers. They require a model that assigns a lead score to each potential customer. This score would indicate the likelihood of conversion, with a higher score suggesting a greater probability of conversion and a lower score indicating a lesser chance.
The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.
These were the following steps that were taken :
Here's a summary of the solution:

1. **Data Understanding**: The data was read and analyzed to understand its structure and content.

2. **Data Cleaning**: Variables with a high percentage of NULL values were dropped. Missing values were imputed where necessary, and new classification variables were created for categorical variables.

3. **Data Analysis**: Outliers were identified and removed. Exploratory Data Analysis was conducted to understand the data distribution. Variables with major data imbalance were dropped.

4. **Dummy Variables Creation**: Dummy variables were created for categorical variables.

5. **Train-Test Split**: The dataset was split into training and testing sets.

6. **Feature Rescaling**: Standard Scaling was used to scale the numerical variables. An initial model was created using a statistical model.

7. **Feature Selection using RFE**: Recursive Feature Elimination was used to identify the top features. The most significant values were selected iteratively, and less important ones were eliminated.

8. **ROC Curve Plotting**: An ROC curve was plotted for the features to assess the model's performance.

9. **Optimal Cutoff Point Determination**: A probability graph was plotted for Accuracy, Sensitivity, and Specificity to determine the optimal probability cutoff point.

10. **Precision and Recall Calculation**: Precision and Recall metrics were calculated based on the train dataset.

11. **Predictions on Test Set**: The model was applied to the test set, and conversion probability was calculated based on Sensitivity and Specificity metrics.
