# Income Prediction

## Overview
This project aims to predict income levels based on demographic and socioeconomic factors using machine learning algorithms.

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


## Data Preprocessing: We performed some data cleaning and preprocessing steps, such as removing missing values, encoding categorical variables, and scaling numerical variables. We also explored the data using pandas, numpy, and matplotlib libraries and generated some plots to understand the relationships between the variables.

## Models
- Algorithms: Logistic Regression, Random Forest, KNN
- Evaluation: Accuracy, Precision, Recall, F1-score

## Usage
1. Install dependencies: `pip install -r requirements.txt`
2. Run the code: `python main.py`

## Results
- Accuracy: [Accuracy Score]
- Precision: [Precision Score]
- Recall: [Recall Score]
- F1-score: [F1-score]
