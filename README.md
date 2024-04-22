# Cookie Business Data Analysis 

## Project Objective 
To gain deeper insights into customer behaviour within our cookie business, particularly their purchasing patterns across various cookie types.
We aim to pinpoint both the top-selling cookie varieties and those experiencing lower sales rates.



## About Data 
The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/urmisha/cookie-business).
| Column           | Description                               | Data Type       |
| -----------------|:-----------------------------------------:|:---------------:|
| Customer ID      | unique identifier assigned to each order  |String     |
| Age              | Age of customer                             |Integer        |
| Age Group        | Age group of customer                          |String     |
| Postcode         | Location of customer                        |String      |
| Gender           | Gender of customer                            |String     |
| Favourite Cookie | Cookie purchased                     |String    |
| Cookies bought each week  |Number of cookies purchased each week  |Integer    |



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
I've attached an Excel [file](https://github.com/Kholeka98/Cookie-business-Analysis/blob/main/Cookie%20business%20project.xlsx) outlining the process for answering these questions. The following follows from our analysis.
| Key Question	| Insights | 
| -----------------|:-----------------------------------------:|
| Which age group buys the most cookies?	|In our dataset, the age group 10-19 emerged as the top purchasers of cookies. Furthermore, individuals aged 10-29 accounted for 57% of all purchases.|
| What is the distribution of cookie purchases by gender?	| In our data, 67% of cookie purchases were made by females, while males accounted for 37% of purchases. |
| Which are the most popular cookies?	| Our analysis revealed that macadamia and  chocolate chip cookies are the most popular choices among consumers. Interestingly, salted caramel cookies constituted only 1% of all purchases. Further investigation is warranted to understand the factors behind this trend.|
|Which postcode area buys the most cookies?|	The area with postcode 2000 stands out as the highest purchaser of cookies in our dataset.|

## Recommendations
Please access my PowerPoint [Presentation](https://github.com/Kholeka98/Cookie-business-Analysis/blob/main/Cookie%20Business%20Data%20Analysis.pptx), which includes the recommendations for this analysis.
