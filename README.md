# E-Commerce EDA Project
This project take a look at an e-commerce dataset. The main aim of the analysis I carried out on it is to generate insights into the purchasing power of customers that frequent the business and to also know the best time customers purchase from the business.


### Project Requirements
E-commerce dataset from Kaggle - https://www.kaggle.com/datasets/utkarsharya/ecommerce-purchases

An IDE for running python- I used VS Code and Jupyter Notebook mostly


### Data Preparation
After importing the data into my IDE, I did a little bit of inspection to see how clean the data was before I start my analysis. To my surprise (Its not common), the data was cleaned up already.

I checked for wrong data types in columns, missing values, and outliers. Everything was perfect and good to go.

Lastly, I did a little bit of feature engineering on the data. I added a column for Email Providers. This was generated from the email column in the dataset.


### Summary of Key Findings

1. Highest and Average Purchase Prices:
   - The highest purchase made by an individual customer amounts to $99.99, while the average purchase across all customers is $50.35.

2. Purchasing Habits by Time of Day:
   - Approximately 50.2% of customers make purchases in the afternoon and evening, a figure that aligns with expectations considering most customers are employed and likely busy with work commitments during the morning hours. Conversely, around 49.8% of customers make purchases in the morning.

3. Distribution of Spoken Languages:
   - Analysis of the languages spoken by customers reveals that Deutsch and Russian are the most prevalent languages, with 1155 occurrences each. In contrast, Simplified Chinese is the least spoken language, with 1059 occurrences.

4. Purchases by Credit Card Type:
   - The analysis of purchases made with various credit card types shows that VISA 16-digit cards lead the pack with a total spending of over $85,000. JCB 16-digit cards closely follow with over $84,000 in total spending. On the other hand, Diners Club/Carte Blanche cards record the least spending, totaling over $37,000.

5. Top Email Providers:
   - The top 5 email providers used by customers are ranked as follows: Hotmail, Yahoo, Gmail, Smith, and Williams.

These key findings shed light on the purchasing behaviors, linguistic diversity, and preferred payment methods of customers on the platform, offering valuable insights for strategic decision-making and targeted marketing efforts.


### Recommendations

1. Optimizing Staffing for Customer Engagement:
   - Given the nearly equal distribution of purchases between morning and evening, it's recommended that the business considers adjusting staffing schedules to ensure adequate coverage during these times. This strategy will accommodate customers' varying schedules and enhance engagement opportunities throughout the day.

2. Enhancing Job Title Categorization Process:
   - A closer examination of job titles revealed a surprising diversity, with all 10,000 entries being unique. Despite recognizing the potential insights that could be gained from analyzing job titles in relation to purchasing behavior, the sheer volume and variability posed a significant challenge. To streamline future analyses and glean actionable insights, it's advised to review the data collection procedures and consider implementing standardized job title categories. This approach will facilitate more efficient analysis and uncover correlations between job roles and purchasing patterns.

3. Improving Data Consistency and Integrity:
   - The presence of similar job titles with minor variations, such as 'Engineer, energy' and 'Energy engineer,' underscores the importance of ensuring data consistency and integrity. To mitigate discrepancies and enhance data quality, it's recommended to implement robust validation processes during data collection and entry. Additionally, exploring automated methods for job title normalization or standardization can help address variations and streamline future analyses.

4. Emphasizing Continuous Improvement in Data Management:
   - Leveraging insights from the analysis of language distribution, credit card usage, and email provider preferences, the business should prioritize continuous improvement in data management practices. By refining data collection procedures, implementing quality assurance measures, and fostering a culture of data-driven decision-making, the organization can enhance its understanding of customer behaviors and preferences, driving strategic initiatives and business growth.

These recommendations aim to address key findings from the analysis while emphasizing the importance of data integrity, consistency, and strategic decision-making in driving business success.
