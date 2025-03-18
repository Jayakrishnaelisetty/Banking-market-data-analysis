# Banking-market-data-analysis
### Exploratory Data Analysis (EDA) Summary: Banking Market Data Analysis  

#### **1. Introduction**  
The EDA aims to uncover patterns, trends, and insights within the banking market dataset. The primary objectives include understanding customer demographics, transaction behaviors, loan distributions, and other key financial metrics affecting the banking industry.  

#### **2. Data Overview**  
- The dataset consists of multiple attributes related to customers, accounts, transactions, loans, and banking services.  
- Key variables include **customer age, income, account balance, loan amount, credit score, transaction frequency, and tenure with the bank**.  

#### **3. Data Cleaning & Preprocessing**  
- Handled missing values by imputation and removal where necessary.  
- Identified and treated outliers in key financial variables (e.g., income, balance, loan amounts).  
- Checked and corrected data types for proper analysis (e.g., converting dates to datetime format).  

#### **4. Univariate Analysis**  
- **Customer Age Distribution:** Most customers fall in the **25-45** age group, indicating a young to middle-aged customer base.  
- **Income Distribution:** Right-skewed, with a few high-income individuals influencing the mean.  
- **Account Balance:** Shows a wide range, with a significant portion of customers maintaining low balances.  
- **Loan Amounts:** Many customers have small to medium-sized loans, with fewer high-value loans.  

#### **5. Bivariate & Multivariate Analysis**  
- **Correlation Analysis:**  
  - Positive correlation between income and account balance.  
  - Negative correlation between credit score and loan amount, indicating riskier borrowers take larger loans.  
- **Loan Approval Trends:**  
  - Higher approval rates for customers with higher income and better credit scores.  
  - Higher rejection rates for customers with a history of defaults.  
- **Transaction Behavior:**  
  - Younger customers tend to have more frequent transactions but lower balances.  
  - High-income customers make larger but less frequent transactions.  

#### **6. Customer Segmentation Insights**  
- **High Net Worth Customers:** Higher balances, lower loan dependence, strong credit scores.  
- **Moderate Income Customers:** Active in banking services, moderate loan dependency.  
- **Low Income Customers:** Frequent transactions, low balances, higher loan needs.  

#### **7. Key Findings & Recommendations**  
- **Targeted Loan Offerings:** Banks can design loan products with flexible terms for low-income customers while ensuring risk mitigation strategies.  
- **Personalized Banking Services:** Offering premium services to high-net-worth individuals based on balance trends.  
- **Customer Retention Strategies:** Younger customers are more active in transactions but may need better incentives to maintain balances.  

This EDA provides valuable insights into customer behavior, financial trends, and risk factors, guiding data-driven decision-making in the banking sector. 
