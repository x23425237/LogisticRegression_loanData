# LogisticRegression_loanData


## Objective: To predict loan approval decisions using various classification models and evaluate their performance using ROC curve analysis.

### Dataset:

- The data contains information on loan applicants, including features such as credit score, income, loan amount, debt-to-income ratio, etc.
- The target variable is the loan approval decision (binary classification: approved or rejected).
### Preprocessing:

- Data cleaning: Handle missing values, outliers, and inconsistent data entries.
- Performing Exploratory Data Analysis (EDA) on the loan data
- Feature scaling: Standardize numerical features for models sensitive to feature scaling (e.g., SVM, K-NN).
- Categorical variables encoding: Convert categorical variables into numerical representations using techniques like one-hot encoding.
#### Model Selection:

- Logistic Regression: A linear model to predict loan approval.
- Random Forest: An ensemble learning method based on decision trees to capture complex patterns in the data.
- Support Vector Machine (SVM): A model aimed at finding the hyperplane that best separates approved and rejected loans.
- K-Nearest Neighbors (K-NN): A distance-based model that classifies loans based on the majority class among neighboring data points.
### Model Training:

- Split the data into training and testing sets (e.g., 80-20 split).
- Train each model on the training data.
### Model Evaluation:

- ROC Curve: Plot the Receiver Operating Characteristic (ROC) curve to evaluate the tradeoff between sensitivity (true positive rate) and specificity (false positive rate) for each model.
- AUC (Area Under the Curve): Compare the AUC scores to determine the overall model performance.
### Model Comparison:

- Evaluate models based on metrics like accuracy, precision, recall, F1-score, and AUC.
- Select the best-performing model based on ROC curve analysis and AUC scores.
### Conclusion:

- Discuss the model that performs best for loan approval prediction.
- Provide insights into the strengths and weaknesses of each model based on the analysis.
