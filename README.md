 # Financial-Statement-Reporting-and-Analysis
 ## Background and Overview
FinBudg is a Software-as-a-Service (SaaS) company founded in 2022, providing innovative software solutions to clients seeking digital services that enhance efficiency and business performance.

The company has significant information on the transactions of the firm, budgets made for each year from 2022 - 2024 and the accounts they deal with. Together, these tables provide a comprehensive view of FinBudg’s financial health — enabling analysis of how actual results compare with budgeted expectations, and offering insights into revenue performance, expense management, and overall profitability.

Insights and recommendations are provided on the following key areas:
- **Financial Overview and Performance:** Analyzed the company’s profitability by comparing expenses across different accounts and account classifications
- **Revenue Analysis:** Compares actual revenue earned by FinBurg with the budgeted revenue, analyzed across different clients and account categories
- **Expense Analysis:** Compares actual expense earned by FinBurg with the budgeted expense, analyzed across different clients and account categories
- **Transaction Analysis:** Evaluted how much FinBurg transact and with what client

An interactive Power BI dashboard can be viewed here: https://app.powerbi.com/groups/me/reports/2f5f3582-efdd-47b6-b874-d872b9a119ed/207b1c0c92d0c0012c87?experience=power-bi

 ## Data Modeling and Structure
 Data provided for analysis was grouped into three main sheets:
- **Transactions:** This table records the actual financial activities of the company — including the amount spent (expenses) and the amount earned (revenue). It shows each account’s real performance over time.
- **Budget:** This sheet outlines the monthly budgeted amounts for each account, both for revenue and expenses. It serves as the company’s financial plan, allowing comparison with actual performance to determine variances.
- **Accounts:** This table provides descriptive information about each account — essentially explaining what each account represents within FinBudg’s financial system. It categorizes the accounts into revenue and expense groups, helping to understand where money is coming from and where it’s going.
 ### Tools Used:
 - Power BI: For building interactive dashboard and data modeling with DAX functions.
 - Figma: Layout and UI designs for logos and card visuals.
### Methodology

 
 <img width="1460" height="1030" alt="Finance model" src="https://github.com/user-attachments/assets/6198d341-e686-413f-8af4-faff1e98ba09" />
 
 ## Execuive Summary
 ### Overview of Findings
Overall, the company recorded more spending activity than income, with 1,003 expense transactions compared to 386 revenue transactions. However, despite the higher number of expense transactions, the value distribution tells a different story. The total revenue generated amounted to $17,958,470, while the total expenses reached $19,406,970, indicating that the company’s expenditures slightly outweighed its earnings. Actual expenses and revenue often move in the same direction, with expenses frequently exceeding the revenue generated. This trend indicates that for FinBudg, operating expenses generally outweighed income, resulting in overall losses. However, in 2024, the company recorded a turnaround — actual revenue exceeded expenses by $299,900, leading to a profit for that year.

<img width="668" height="252" alt="overview 1" src="https://github.com/user-attachments/assets/572c6e57-a1cc-4a1e-9eda-5bb0d73695a8" />

 <img width="527" height="498" alt="overview 2" src="https://github.com/user-attachments/assets/b34453ab-740f-47cc-a383-d13780c38ec7" />

### Financial Overview and Performance
- Net profit
### Revenue Analysis
- There is a clear upward trend in revenue, with noticeable peaks typically occurring toward the end of the year, particularly in November and December. Overall,   revenue has shown consistent growth from 2022 to 2024, with actual revenue frequently surpassing the budgeted amounts, even if only by slight margins. Both the budgeted and actual revenue tend to move closely together, with actual revenue exceeding projections in specific months such as April 2023, July 2023, June 2024, July 2024, and October 2024.
Notably, June and July appear to mark periods of strong seasonal performance, with momentum often building through the year and reaching its highest levels by December.
- Primary sources of revenue:
     - **Accounts:** FinBudg’s main sources of revenue are drawn from three key accounts: 40100 SaaS Revenue, 40200 Product Revenue, and 70100 Interest Income. Among these, SaaS Revenue stands out as the largest contributor, accounting for roughly two-thirds of total income.
    - **Transaction Types:** Revenue is primarily generated through Invoices and Deposits, reflecting standard billing and collection processes for service and product-based income.
    - **Clients/Vendors:** The top three revenue-generating clients include a mix of small and medium-sized businesses (SMBs), along with key corporate accounts such as GlobalTech and TechCorp Inc.
- There were no months where revenue fell noticeably below the planned amount, except for February and November 2024, where a slight shortfall was observed.

 <img width="1349" height="849" alt="rev" src="https://github.com/user-attachments/assets/06609470-a8a5-4bbe-b8bc-6a75010884a2" />

 ### Expense Analysis
 - Spending increased sharply in July, prompting a closer look at the data by year. In 2022, expenses rose dramatically from $39,400 in June to $539,530 in July, leading me to investigate the cause of this spike. I found that out of the 39 transactions recorded in July 2022—one of the highest transaction counts of the year—only 8 were revenue transactions. Notably, on July 15, 2022, there was a significant expense charge of $87,500 for payroll. This suggests that the sharp increase in spending during this period was largely due to payroll-related expenses, possibly reflecting a backlog of employee salaries being cleared that month.
 - The top spending categories are G&A, S&M, R&D and CS
 - The top five vendors that received the highest expense payments were ADP, Hardware Inc, United Health, AWS, and Google Ads. Among them, ADP accounted for the largest share of expenses — primarily due to its role in managing employee payroll, salaries, and wages, which explains its position as one of the highest expense categories.

<img width="1337" height="846" alt="Exp" src="https://github.com/user-attachments/assets/b02f745d-4103-44fb-aa70-4e34bdb53b6d" />
<img width="1296" height="445" alt="Exp1" src="https://github.com/user-attachments/assets/c0bd9eeb-ee50-4f6f-ad8e-7238260ec7cf" />

### Transaction Analysis
- Overall, based on the volume of transactions, there were significantly more expense transactions than revenue transactions. However, when measured in terms of value, revenue accounted for a larger share, despite having a lower transaction count.
- More transactions were recorded under the General & Administration category, which makes sense as it is the only category that includes both revenue and expense transactions.

<img width="1341" height="853" alt="transc" src="https://github.com/user-attachments/assets/ed495fca-8387-4f1b-9c82-0d6da2c2b21d" />

## Recommendation
<img width="1676" height="938" alt="Finance DB 1" src="https://github.com/user-attachments/assets/b2f37c52-9224-40b2-8775-b2a08c8657f7" />

<img width="1673" height="933" alt="Finance DB 2" src="https://github.com/user-attachments/assets/c5bef91f-75d3-4f27-a185-1cd96c36dc8b" />

<img width="1681" height="940" alt="Finance DB 3" src="https://github.com/user-attachments/assets/60053803-4ecf-42d5-b610-9d22b9fb6d0d" />

<img width="1677" height="933" alt="Finance DB 4" src="https://github.com/user-attachments/assets/7680278d-d0a1-4d2c-87cb-c5ba51364e1b" />
