
# Personal Loan Prediction Project

This project aims to predict whether a customer will take a personal loan based on various features such as age, experience, income, ZIP code, family size, education level, credit card usage, securities account status, CD account status, and online banking usage.

## Dataset

The dataset used in this project is called "Bank_Personal_Loan_Modelling.csv". It contains information about customers' banking activities and whether they accepted the personal loan offer.

## Project Workflow

1. **Data Exploration and Preprocessing**: 
   - Inspecting the data dimensions, statistical aspects, and checking for null values.
   - Exploring correlations between features using visualizations.
   - Handling negative values in the 'Experience' feature.
   - Analyzing the distribution of data.
   - Renaming features for consistency.

2. **Exploratory Data Analysis (EDA)**:
   - Conducting further exploration and visualization of the data using Tableau.
   - Observing correlations between features and identifying patterns.

3. **Model Development**:
   - Splitting the dataset into training and testing sets.
   - Implementing logistic regression using both scikit-learn and statsmodels.
   - Evaluating the model's performance using metrics such as accuracy, confusion matrix, sensitivity, specificity, false positive rate, positive predictive value, and negative predictive value.

4. **Model Evaluation**:
   - Visualizing the Receiver Operating Characteristic (ROC) curve and determining the area under the curve (AUC).
   - Calculating precision and recall scores on both the training and testing sets.
   - Making predictions on the test set and evaluating the model's performance.

5. **Conclusion**:
   - The model demonstrates strong predictive performance with an accuracy of approximately 95% on the test data.
   - Precision and recall scores indicate a balanced performance in predicting positive instances.
   - Suggestions for further improvement, such as exploring optimal cutoff points and considering alternative models like random forests.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

