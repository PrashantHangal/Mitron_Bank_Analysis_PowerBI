# Mitron_Bank_Analysis_PowerBI

-(Provide Insights to the Product Strategy Team in the Banking Domain)

## About Mitron Bank 

Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market.

## Objective of the Project 

The objective is to analyze this data and provide actionable, data-driven recommendations to guide Mitron Bank in tailoring the new credit cards to customer as per needs and market trends. 

## Problem Statement   

 * **Demographic classification**: Classify the customers based on available demography such as age group, gender, occupation etc. and provide insights based on them.
   
 * **Avg income utilisation %:** Find the average income utilisation % of customers (avg_spends/avg_income). This will be your key metric. The higher the average income utilisation %, the more is their likelihood to use credit cards.
   
 * **Spending Insights:** Where do people spend money the most? Does it have any impact due to occupation, gender, city, age etc.? This can help you to add relevant credit card features for specific target groups.

 * **Key Customer Segments:** By doing above, you should be able to identify and profile key customer segments that are likely to be the highest-value users of the new credit cards. This includes understanding their demographics, spending behaviours, and financial preferences. 

 * **Credit Card Feature Recommendations:** Provide recommendations on what key features should be included in the credit card which will improve the likelihood of credit card usage. This should be backed by the insights from data provided and also some secondary research on the internet for this.
#

## Demographic Classification:   

For demographic classification, I have conducted a thorough customer demographic analysis using Power BI, and here are the key findings presented in a visually engaging manner:

#
<p align="center">
  <img src="https://github.com/PrashantHangal/Mitron_Bank_Analysis_PowerBI/blob/main/Demographic_analysis.jpg?raw=true" alt="Demographics" width="100%" />
</p>
#

### Total Customers:

The dataset encompasses a substantial pool of 4000 customers, forming the foundation of our analysis.

### Gender Dynamics:

 * The majority of our customer base comprises males, accounting for 64.93%, indicating a slightly male-dominated demographic.
 * However, the substantial presence of females (35.08%) highlights a diverse customer landscape.

### Age Group Profiling:

 * The age group 25-35 emerges as the most significant segment, with 1498 customers. This group, especially males, exhibits a strong presence.
 * Customers aged 35-45 also form a substantial portion (1273), demonstrating a balanced distribution between genders.
 * The 45+ age group, while smaller, remains a noteworthy segment that shouldn't be overlooked.

### City-wise Distribution:

 * Mumbai takes the lead in terms of customer concentration, with 1078 customers, predominantly males.
 * Other major cities like Chennai, Bangalore, and Delhi NCR also contribute significantly to our customer base.

### Occupational Insight:

 * Salaried IT Employees represent a large portion of our customers (1294), showcasing a tech-centric demographic.
 * The diversity in occupations, including freelancers and business owners, presents an opportunity to tailor services for varied professional needs.

### Marital Status Overview:

 * A significant majority of our customers are married (78.41%), emphasizing the importance of considering family-centric financial solutions.
 * Unmarried customers, though a smaller segment, still constitute a substantial 21.6% of our customer base, which emphasizing for their high end lifestyle.
#

## Income Utilization & Spending Analysis  

In pursuit of illuminating critical insights into customer spending patterns and understanding the average income utilization across diverse segments, a dedicated analytical exploration has been undertaken. To facilitate a comprehensive understanding, a bespoke "Customers Spend Analysis" page has been meticulously crafted within Power BI. This page serves as the epicenter for unraveling intricate details, housing a plethora of Key Performance Indicators (KPIs) and insightful charts and graphs.

#
<p align="center">
  <img src="https://github.com/PrashantHangal/Mitron_Bank_Analysis_PowerBI/blob/main/Income_analysis.jpg?raw=true" alt="income_analysis" width="100%" />
</p>
#

### Average Income Utilization:

* Average Income Utilization stands at 42.82%

### Key Metrics:

 * Total Income in 6 months: $1240M
 * Total Spends in 6 months: $531M

 #  
<p align="center">
  <img src="https://github.com/PrashantHangal/Mitron_Bank_Analysis_PowerBI/blob/main/Expenditure_analysis.jpg?raw=true" alt="exp_analysis" width="100%" />
</p>
#

### Income, Spend, Utilization by Age Group:

 * Age group 25-34 exhibits the highest income, spend, and utilization (43.66%).
 * Second-highest is the 35-45 age group with a utilization rate of 46.52%.

### Total Spends by Category:

 * Highest spending in bills category ($105M) with an average utilization of 46%.
 * Other significant categories: Grocery ($86M), Electronics ($80M), and the least in Others category ($16M).

### Income, Spend, Utilization by Occupation:

 * Salaried IT employees lead in income ($477M), spend ($244M), and utilization (51.04%).
 * Business Owners show an income of $265M, spend of $88M, and a utilization rate of 33.22%.
 * Government employees have the lowest utilization at 29%.


### Income, Spend, Income Utilization by City:

 * Mumbai outshines with the highest income and spend, resulting in a utilization rate of 51.43%.
 * Chennai, Delhi NCR, Bengaluru, and Hyderabad follow with varying utilization rates.

#
<p align="center">
  <img src="https://github.com/PrashantHangal/Mitron_Bank_Analysis_PowerBI/blob/main/Financial_Transaction_analysis.jpg?raw=true" alt="FT_analysis" width="100%" />
</p>
#

### Total Spend by Payment Type:

 * Credit cards dominate spending, accounting for $216M with a utilization rate of 17.45%.
 * Other payment types include UPI, debit cards, and net banking.

### Total Spend by Gender:

 * Males lead in spending with $357M, while females contribute $154M.

### Spend by Marital Status:

Married individuals top the spending charts with $429M, surpassing unmarried individuals at $102M.

### Total Spend by Month:

September emerges as the highest spending month, accounting for $116M, constituting 21.84% of the total spend.

### Income Utilization by Gender:

Males exhibit a higher income utilization rate at 44.39%, compared to females at 39.92%.

### Income Utilization by Marital Status:

Singles show a utilization rate of 43.06%, slightly surpassing married individuals at 42.77%.


#
## Recomendation for Next Credit Card

To improve the likelihood of credit card usage among the identified target customers (salaried employees, self-employed individuals, and freelancers), consider incorporating the following key features in the credit card:

#### Tailored Rewards Program:

Create a rewards program that aligns with the spending patterns of salaried employees, self-employed individuals, and freelancers. This could include cash back on common categories of spending such as groceries, dining, and business-related expenses.

#### Flexible Payment Options:

Offer flexible payment plans to accommodate different income structures. This could include customizable monthly payment options, allowing users to adjust their payment schedule based on their cash flow.

#### Expense Tracking and Budgeting Tools:

Provide built-in tools or partner with budgeting apps to help users track their expenses, categorize spending, and set budget goals. This can be particularly beneficial for freelancers and self-employed individuals managing variable income.

#### Low Annual Fees and Interest Rates:

Keep annual fees competitive and offer reasonable interest rates to attract and retain customers. Consider providing introductory offers, lower rates for loyal customers, or special promotions for specific spending categories.

#### Contactless and Mobile Payments:

Ensure the credit card supports contactless payments and integrates with popular mobile payment platforms. This adds convenience for users who prefer digital and contactless transactions.

#### Security Features:

Implement advanced security features such as fraud alerts, biometric authentication, and virtual card numbers to enhance the safety of transactions. Communicate these security measures to build trust among users.


𝗞𝗲𝘆 𝗧𝗮𝗸𝗲𝗮𝘄𝗮𝘆𝘀:

1. **Customer Preferences**: Explored age groups and payment preferences crucial for tailoring the ideal credit card in our imaginary world. 
2. **Income Insights**: Uncovered income details, discovering that Mumbai leads in earnings and IT employees are the highest earners.
3. **Spending Patterns**: Identified peak spending times and what customers spend on – vital for our imaginary bank's strategy. 
4. **Income Utilization**: Discovered how people use their money, revealing that IT employees maximize their spending.
