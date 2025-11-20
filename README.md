# Telco Customer Churn Analysis

This project analyzes customer churn patterns using the Telco Customer Churn dataset from kaggle. The goal of this project is to identify key drivers of churn, build a predictive model, and offer recommendations that a busines could use to reduce churn. This project represents a step towards a career in data analysis.

## Project Overview

Customer churn is a major revenue risk for subscription based companies. Not only does losing customers hurt revenue, but finding new ones cost morney.
In this project I will study the data set and explore:

- Which customers are most likely to churn
- Which features correlate with retention
- How features interact with one another
- Use a simple predictive model to confirm findings
- Actionable, data driven recommendation for reducing churn

all analysis is done in a Jupyter Notebook using Python

## Tools and Techniques

**Language and Libraries**
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- statsmodels

**Skills Demonstrated**
- data clearning and preprocessing
- EDA
- Logistic Regression modeling
- Data Visualization
- Business interpretation and reporting

## Key Insights
Contract, tenure, and monthly payments account for almost all of the predictive signal in this data set. Almost all the other features that showed significant values were a result of a relationship with one of those three core features.

### Contract Type
Customers with month-to-month contracts churned at a much higher rate that those with annual or biannual contracts.

### Tenure
Customers in the first 6 months of tenure have a dramatically higher churn rate

### Monthly Charges
Higher monthly charges are associated with higher churn rates

## Predictive Model
- feature encoding
- train/test split
- model fitting
- accuracy and classification report
- business implications of predictive modeling

## Business recomendations
The top priority is to encourage long term contracts. Short term contracts are the number one indicator of churn. Almost all of the high churn rates that appear in the other categorical features are explained by contract type when looking at the data more closely. Because of this, encouraging longer contracts would reduce churn rates across almost all features. This can be achieved by discounting the first year or offering various promotions.

The second priority is to increase retention for customers in their first six months of tenure. I recommend promotions to extend their tenure such as discounting a 6 month extension. Additionally ensuring customer satisfaction within those first six months is important. This can be achieved by monthly check ins to see what they are/aren't satisfied with.

The final priority is to take care of customers with higher than average monthly bills, especially those in the $70-$100 range. This can include things like bundling premium services to reduce their financial aches. Similar to customers in their first six months, it's important to check in on these customers and make sure they're happy. Not only are they at a high risk of leaving, they are also high value customers.

Although a lot of the categorical data's churn rates can be attributed to contract types, that doesn't mean the data isn't useful. For example, senior citizens have a very high churn rate. This is because they are more inclined to have month to month contracts. To help decrease churn in that sector senior discounts could be offered for 1+ year contracts. This would help reduce costs for seniors as well as increase retention. Similarly, people with partners and dependents have lower churn rates, but that's also explained by the fact that they are more likely to have long term contracts. Because of this advertisements targetting families may be effective because that could result in a higher number of customers with long term contracts.

## My goals in this project

demonstrate:
- Ability to perform real-world EDA  
- Strong understanding of customer behavior analytics  
- Ability to communicate findings clearly  
- Early machine learning experience  
- Skills aligned with entry-level data analyst roles
