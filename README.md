# Banking_Domain_Report
In this project , we aim to perform the data analysis on bank customers data to identify the reasons why customers leave the bank. Tools used for the analysis are Power BI, SQL and Excel.
# Project Overview
The aim of this project is to analyze the bank customers data to identify the factors contributing the customers churn using Power BI, SQL and Excel.
To gather valuable insights from the analysis to understand patterns, trends and correlations associated with bank customers data.
To provide recommendations to the bank to mitigate churn.it allows banks to address customer needs, improve retention strategies, and save costs associated with acquiring new customers. Identifying at-risk customers allows banks to implement personalized retention strategies, improving customer experience and reducing attrition rates.
Problem Statement
The bank is facing significant challenge with high churn rates and it is aiming to reduce costs linked to customer acquisition. Understanding the reasons behind customer churn is pivotal for tailoring services and implementing targeted retention efforts. This allows the bank to address customer needs, refine retention strategies and identify at-risk customers for personalized retention strategies.

# Data Source
Domain: Banking Domain
Dataset Name: Bank_Churn.csv ActiveCustomer.xlsx CreditCard.xlsx CustomerInfo.csv ExitCustomer.xlsx Gender.xlsx Geography.xlsx
Dataset Type: Excel and CSV Datatypes
Dataset Size: 10,000 customers data spanning 4 years.
# Data Cleaning/Preparation
Checked for presence of duplicates and eliminated them.
Removing irrelevant columns which does not associated with customer churn.
Data type standardization.
Formatting dates for consistency.
Formatted numerical data for consistency.
Handling the text values and removed special characters in name.
Handled null values.
# Inferences
inferences from the analysis:

Total customers associated with the bank are 10,000.
Churn Rate is 20.37 % .Which is higher than the healthy range , churn rate of 5-7% annually is considered average in the banking industry. So the bank should consider this as the serious problem and take necessary actions.
Retention Rate 79.63 %. High retention rate indicates customer satisfaction and loyalty. Anything above 90% might be considered healthy.
Active Customer Rate 51.51 %. Desired range for active customer rate is above 70-80%. These desired ranges can vary based on the bank's services and customer engagement strategies.Inactive Customers have more churn rate.
Credit Card Holder Rate is 70.55 %. Bank is doing good in this case. Typically, a rate higher than 50-60% might be considered good, but this can vary widely. But, churn rate is high in case of the credit card holders. People with fair and poor credit score are leaving the bank.
Customers have a varying number of products, typically ranging from 1 to 4. Products Per Customers is 1.53. Around 3-4 products per customer is often seen as a good benchmark. Most of customers has 1 or 2 products and churn rate is more in that range.
Average Tenure is 5 Years, Indicating the level of loyalty and the bank's ability to retain its customer base. Most of the customers are leaving the bank within 4 to 5 years.
Average age 39. Churn rate is high in case of age Late Adulthood age group.
Average Balance Per Customer is around 75k . Customers with a higher balance churn more which would be worrying to the bank as this impacts their source of loan capital.
Churn Rate is minimum in Year 2016 that is 19.27 % and maximum in year 2017 that is 22.35 % . Also we have forecasted the Churn rate for the next four quarter predicting churn rate between lower bound 15 0r 16 % and the upper bound is 24 to 25 % with 95 % confidence level.
Churn rate is high in female compared of male even though there are more male customers.
Churn Rate is highest in Germany that is 32.44 % and for both france and spain churn rate is around 16%.
# Recommendations:
Enhance customer service, resolving customers issues , offer personalized experiences to increase satisfaction.
Implement loyalty programs, rewards for long-term customers to reduce churn.
Regularly engage with customers via multiple channels, offering relevant updates and personalized offers.
Collect and act on customer feedback to address pain points and enhance overall satisfaction
Encourage active participation in banking activities, offer exclusive benefits, and personalize services based on customer behavior.
Upselling and Cross-Selling; Train staff to recommend complementary products or services to existing customers based on their profiles and behavior.
Customer Segmentation: Segment customers based on behavior and preferences, offering tailored packages to each segment. Like Investment products, insurance , credit cards and loans.
Profitability: Longer-tenured customers tend to be more profitable as they utilize more services and products over time.
Acquiring new customers is more expensive than retaining existing ones.All these increses Average Customer Lifetime Value
# Limitations
External factors like economic conditions and competitive landscape impacting customer churn are not considered in analysis.
Analysis might not facilitate personalized strategies for individual customer retention due to generalized findings from aggregated data.
Analysis might provide insights at a specific point, lacking continuous monitoring and adjustment to adapt to evolving customer behaviors.
Analysis is based on the historical data and this may be not true in future.
This project will not accurately predict the customer churn in future.
