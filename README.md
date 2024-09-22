# Banking-Financial-Insights-in-Banking-Data--Power-BI
[DASHBOARD PDF](https://drive.google.com/file/d/1tYjZu1ycI76ZCpSQuCGqjvEodUKHlnal/view?usp=sharing)

![Himanshu bank data analysis part-2 Dashboard_page-0001](https://github.com/user-attachments/assets/9427f270-69e0-4daf-8046-502f77cfa52e)
![Himanshu bank data analysis part-2 Dashboard_page-0002](https://github.com/user-attachments/assets/8f80ede6-4603-4a3a-8125-eabd524c1da5)
![Himanshu bank data analysis part-2 Dashboard_page-0003](https://github.com/user-attachments/assets/ec246f2e-7958-4d60-9dfc-53f1268baf52)



### **Objective**

Your task is to employ Power BI to analyze these banking datasets, aiming to unravel the intricate patterns and behaviors within the data. This involves in-depth data cleaning, robust data modeling, and strategic use of DAX for complex analytics. Your goal is to create a comprehensive, interactive dashboard that not only illustrates transactional trends and customer profiles but also offers a holistic view of the banking ecosystem. This analysis should include understanding customer transaction behaviors, identifying relationships between account characteristics and financial health, and exploring factors influencing credit scores and loan management. Your insights will guide FinInsight Group in advising banking institutions on optimizing their services, enhancing customer satisfaction, and managing financial risks effectively.

The "BankingDataset1.xlsx" file contains the following columns:

1. **TransactionID**: A unique identifier for each transaction. 
2. **AccountNumber**: The account number associated with the transaction. (Foreign Key)
3. **TransactionType**: The type of transaction (e.g., Transfer, Deposit, Withdrawal, Payment).
4. **Amount**: The amount of money involved in the transaction.
5. **TransactionDate**: The date when the transaction occurred.
6. **BranchCode**: The code of the bank branch where the transaction took place.
7. **Currency**: The currency in which the transaction was made.
8. **TransactionTime**: The time of day when the transaction occurred (in hours).

The "BankingDataset2.xlsx" file contains the following columns:

1. **AccountNumber**: A unique identifier for each account, corresponding to 'AccountNumber' in "BankingDataset1.xlsx". (Primary Key)
2. **AccountHolder**: The name of the account holder.
3. **AccountType**: The type of account (e.g., Credit, Loan, Checking).
4. **Balance**: The current balance of the account.
5. **InterestRate**: The interest rate applicable to the account.
6. **CreditScore**: The credit score of the account holder.
7. **OpeningDate**: The date when the account was opened.
8. **LoanAmount**: The amount of loan associated with the account (if applicable).
9. **AccountHolderDetails:** Details about account holders - employment sector, years at current residence, and city of residence etc.   



In this project, I leveraged Power BI to conduct a comprehensive analysis of banking datasets, focusing on 'Banking Transactions' and 'Customer Account Details.' Through meticulous data cleaning, robust data modeling, and strategic DAX utilization, I developed an interactive dashboard that visualizes transactional trends and customer profiles. This dashboard provides a holistic view of the banking ecosystem, offering actionable insights that guide financial institutions in optimizing their services, enhancing customer satisfaction, and effectively managing financial risks.


**1.Comprehensive Data Analysis:** Conducted in-depth analysis of 'Banking Transactions' and 'Customer Account Details' datasets, uncovering intricate patterns and behaviors critical to financial decision-making.

**2.Data Cleaning & Modeling:** Executed thorough data cleaning processes and implemented robust data modeling techniques to ensure the integrity and accuracy of complex banking datasets.

**3.Strategic DAX Utilization:** Applied strategic use of DAX for complex financial analytics, enabling detailed exploration of customer transaction behaviors and relationships between account characteristics and financial health.

**4.Interactive Dashboard Development:** Designed and developed a comprehensive Power BI dashboard that visualizes transactional trends, customer profiles, and provides a holistic view of the banking ecosystem.

**5.Insightful Reporting:** Delivered actionable insights through the dashboard, guiding banking institutions in optimizing services, enhancing customer satisfaction, and effectively managing financial risks.

**6.Optimization of Banking Operations:** Leveraged data-driven insights to advise FinInsight Group on strategies for improving banking performance, including customer relationship management and risk assessment.

## Dashboard & Insights
![Himanshu bank data analysis part-2 Dashboard_page-0001](https://github.com/user-attachments/assets/b6d0cdb9-e9e7-49f5-8c9b-0ece25c9b932)

# **Transactions & Balance Insights:**

**Hourly Transaction Trends:** The busiest times for transactions are 11 AM and 3 PM, while the largest amounts are seen at 2 AM and 11 AM.

**Quarterly Transaction Trends:** Transaction volume remains stable, but credit and debit transactions show opposite trends.

**Historical Trends & Forecast:** Transaction volumes peak from July to September, with little fluctuation overall. A slight decline in volume is forecast for the next quarter.

**Average Account Balance:** Savings accounts have the highest average balance compared to other account types.

**High-Value Transactions:** Transactions above $5,000 are flagged as high value, making up 2.5% of total transactions, with a lower frequency than regular transactions but often considered for fraud.

**Rare Transaction Types:** Rare transactions, mostly under the "Payment" category, show low value but differ from common types like Transfer, Withdrawal, Deposit, or Payment.


