# Business-Case-Walmart---Confidence-Interval-and-CLT

### Insights: 
-   **Analyzed** Walmart's Black Friday transactional dataset using Python libraries and statistical methods to identify key factors influencing customer purchase behavior and assess gender-based spending differences.
-   **Highlighted** that male customers have higher spending per transaction, with a 90% confidence level showing their purchase amounts range between $9,436 and $9,440, compared to $8,733 to $8,736 for female customers.
    
-   **Demonstrated** that even at a 95% confidence level, male customers consistently spend more, confirming the trend of higher average expenditures compared to female customers.
    
-   **Showed** that female customers have more consistent spending patterns, with a narrower purchase range, indicating less variation in their spending habits.
    
-   **Confirmed** that Walmart can leverage these insights by targeting marketing strategies toward male customers for higher average spending, while also exploring promotions to boost female customers' purchase amounts.

### About Walmart

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

  
### Business Problem

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).

  
### Dataset

The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:

| Features                     | Description                                     |
|------------------------------|-------------------------------------------------|
| `User_ID`                    | User ID                                         |
| `Product_ID`                 | Product ID                                      |
| `Gender`                     | Sex of User                                     |
| `Age`                        | Age in bins                                     |
| `Occupation`                 | Occupation (Masked)                             |
| `City_Category`              | Category of the City (A, B, C)                  |
| `StayInCurrentCityYears`     | Number of years stay in current city            |
| `Marital_Status`             | Marital Status                                  |
| `ProductCategory`            | Product Category (Masked)                       |
| `Purchase`                   | Purchase Amount                              