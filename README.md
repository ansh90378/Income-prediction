# Income Prediction

## Overview
Predicting income levels through the analysis of demographic and socioeconomic factors using advanced machine learning algorithms. By leveraging cutting-edge techniques, we aim to develop a predictive model that can accurately estimate income levels based on various key indicators. Through this endeavor, we strive to contribute valuable insights into understanding income disparities and facilitating informed decision-making in areas such as finance, policy, and social welfare.

## Dataset Description:
1. Demographic Information:
- Age: Age of the individual.
- Gender: Gender of the individual.
- Marital Status: Marital status of the individual.

2. Employment Details:
- Enrolment in Educational Institution: Whether the individual is enrolled in an educational institution.
- Employment Commitment: Full or part-time employment status.
- Employment Status: Whether the individual owns a business or is self-employed.
- Wage per Hour: Hourly wage of the individual.
- Weeks Worked in a Year: Number of weeks worked in a year.
- Industry and Occupation Codes: Codes indicating the industry and occupation of the individual.

3. Financial Information:
- Gains: Financial gains.
- Losses: Financial losses.
- Dividends from Stocks: Dividends received from stocks.

4. Family and Veteran Status:
- Household and Family Statistics: Detailed household and family statistics.
- Veteran Benefits: Benefits received by veterans.

Target Variable:
- Income Above $50,000: Binary classification indicating whether the individual's income is above
$50,000.


## Data Preprocessing: 
We performed some data cleaning and preprocessing steps, such as removing missing values, encoding categorical variables, and scaling numerical variables. We also explored the data using pandas, numpy, and matplotlib libraries and generated some plots to understand the relationships between the variables.

## Models
- Algorithms: Logistic Regression, Random Forest, KNN
- Evaluation: Accuracy, Precision, Recall, F1-score

## Results
# Accuracy: [Accuracy Score]
  Accuracy is a metric that measures how often a machine learning model correctly predicts the outcome.
  
  $$
  Accuracy = Correct Predictions / All Predictions 
  $$


# Precision: [Precision Score]
  Precision is a metric that measures how often a machine learning model correctly predicts the positive class.

  $$
  Precision = True Positives / (True Positives + False Positives)
  $$


# Recall: [Recall Score]

  $$
  Recall = True Positives / (True Positives + False Negatives)
  $$

  
# F1-score: [F1-score]

  $$ 
  F_1 = True Positives / True Positives + 0.5(False Positives + False Negatives)
  $$

