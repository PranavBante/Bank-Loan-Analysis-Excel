# Bank-Loan-Analysis-Dashboard

##  Project Overview
This dashboard is designed to analyze the lending operations of a financial institution. It assesses the health of the loan portfolio, identifies trends in borrower demographics, tracks repayment performance, and highlights potential risks.

### The project demonstrates skills in:

- <b> Excel Data Cleaning & Processing </b>
- <b> Advanced PivotTables & Data Modeling </b>
- <b> KPI Calculation & Risk Assessment </b>
- <b> Interactive Dashboard Design </b>
- <b> Demographic & Financial Analysis </b>

## Dataset Description
The dataset contains comprehensive loan records, including borrower details, loan terms, and repayment status. Below is the data dictionary explaining key columns.

| Column Name        | Description                            |
| ------------------ | -------------------------------------- |
| Account ID         | Unique identifier for each loan        |
| Loan Amount        | Amount requested by the borrower       |
| Funded Amount      | Amount actually disbursed              |
| Loan Status        | Current, Fully Paid, Charged Off, etc. |
| Grade / Sub Grade  | Loan risk classification               |
| Interest Rate      | Annual interest rate                   |
| Term               | Loan tenure (36 / 60 months)           |
| Purpose            | Reason for loan                        |
| Home Ownership     | Rent / Own / Mortgage                  |
| Annual Income      | Borrower’s yearly income               |
| Issue Date         | Loan disbursement date                 |
| State / Region     | Borrower location                      |
| Delinquency Status | Past due indicator (Y/N)               |


## Dashboard Preview

<img width="1141" height="524" alt="Screenshot 2026-01-08 123544" src="https://github.com/user-attachments/assets/b5e1d6fb-9dc8-48f6-ae25-05867e9e3b82" />

## Features

#### 1. Key KPIs

 - <b>Total Funded Amount:</b><i> The total principal amount disbursed to borrowers.</i>
 - <b>Total Interest Earned:</b><i> Revenue generated from loan interest.</i>
 - <b>Total Collections:</b><i> Aggregate amount collected (Principal + Interest).</i>
 - <b>Delinquency Rate:</b><i> Percentage of loans that are past due.</i>
 - <b>Average Interest Rate:</b><i> The weighted average rate across the portfolio.</i>

#### 2. Visual Insights
- <b>Loan Status Distribution:</b><i> Breakdown of Active, Fully Paid, and Non-Performing Assets (NPA).</i>
-	<b>Demographic Analysis:</b><i> Loan distribution by Gender, Age Group, and Religion.</i>
-	<b>Geographic Trends:</b><i> State and Region-wise lending performance.</i>
-	<b>Purpose-wise Funding:</b><i> Analysis of loans for Business, Agriculture, and other categories.</i>
- <b>Time-Series Trends:</b><i> Yearly and monthly disbursement trends.</i>
  
#### 3. Interactive Filters
- <b>Year / Quarter:</b><i> Filter data by disbursement timeline (e.g., 2017-2020).</i>
- <b>Region / State:</b><i> Drill down into specific geographic markets.</i>
- <b>Loan Grade:</b><i> Filter by risk grade (A, B, C, etc.).</i>
- <b>Purpose Category:</b><i> Filter by loan usage (Agriculture, Business, Personal).</i>
  
## Tools Used

-	<b> Microsoft Excel:</b><i> Primary tool for data storage and manipulation. </i>
-	<b> PivotTables:</b><i> Used for aggregating loan data by various dimensions. </i>
-	<b> PivotCharts:</b><i> Visual representation of trends and distributions. </i>
-	<b> Slicers:</b><i> To enable interactive filtering on the dashboard. </i>
-	<b> Data Cleaning:</b><i> Handling missing values and standardizing formats (Date, Currency). </i>
  
## Key Insights
#### 1. High Portfolio Health
The portfolio demonstrates exceptional performance with a Delinquency Rate of only ~1.56%, indicating strict underwriting standards and high borrower quality.
#### 2. Significant Gender Disparity in Lending
The data reveals a massive focus on female borrowers (~$750M funded) compared to male borrowers (~$273K). This suggests a business model heavily skewed towards women-centric financing or micro-finance groups.
#### 3. Strong Repayment Behavior
The majority of loans are either "Active" (~$401M) or "Fully Paid" (~$187M). Non-Performing Assets (NPA) constitute a very small fraction (~$5.8M) relative to the total volume.
#### 4. Youth & Middle-Age Dominance
Borrowing is most prevalent among the 26-35 and 36-45 age groups, which combined account for over $500M of the loan book.
#### 5. Business & Agriculture Lead Funding
The primary drivers for borrowing are Business loans ($36M), highlighting the productive nature of the deployed capital.

## Recommendations
#### 1. Sustain Female-Centric Products 
Given the success and volume of female borrowers, the bank should continue to tailor products (e.g., lower rates, flexible terms) specifically for women entrepreneurs to maintain this stronghold.
#### 2. Monitor "Active" Loan Transition
With ~$401M in Active loans, implementing early warning systems for the 26-35 age demographic could prevent future delinquencies as this group holds the largest share of debt.
#### 3. Diversify Male Borrower Base
There is a largely untapped market among male borrowers. Creating targeted marketing campaigns for men in the 26-45 age bracket could diversify the portfolio risk.
#### 4. Expand High-Performing Regions
Regions with high activity should be analyzed for further expansion. Branch presence or digital marketing in neighboring high-potential districts could boost revenue.
#### 5. Cross-Sell to "Fully Paid" Customers
Customers with "Fully Paid" status ($187M volume) represent low-risk opportunities. They should be targeted for premium loan products or higher-ticket business loans.
#### 6. Review "Write-Off" Patterns
Although low, analyzing the specific attributes (Grade, Purpose) of the loans that went to "Write Off" can help refine future credit scoring models.

