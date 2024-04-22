# Cookie Business Data Analysis 

## Project Objective 
To gain deeper insights into customer behaviour within our cookie business, particularly their purchasing patterns across various cookie types.
We aim to pinpoint both the top-selling cookie varieties and those experiencing lower sales rates.



## About Data 
The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/urmisha/cookie-business).
| Column           | Description                               | Data Type       |
| -----------------|:-----------------------------------------:|:---------------:|
| Customer ID      | unique identifier assigned to each order  | String     |
| Age              | Age of customer                             |  Integer        |
| Age Group        | Age group of customer                          | String     |
| Postcode         |  Location of customer                        | String      |
| Gender           | Gender of customer                            | String     |
| Favourite Cookie | Cookie purchased                     | String    |
| Cookies bought each week  |Number of cookies purchased each week  |  Integer    |



## Approach Taken 
### Dataset Preparation
- The dataset was checked for duplicates, missing values, and inconsistency in spelling.
- To maintain consistency in the total number of cookies bought each week, a single randomly generated value in the 'Cookies bought each week' field was replaced with an estimate derived from the median of the values within the same column.


## Business Questions to answer
- Which age group buys the most cookies?
- What is the distribution of cookie purchases by gender?
- Which are the most popular cookies?
- Which postcode area buys the most cookies?

## Results
