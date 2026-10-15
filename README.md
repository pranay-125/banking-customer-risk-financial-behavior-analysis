```html
<h1 align="center">🏦 Banking Customer Risk & Financial Behavior Analysis</h1>

<p align="center">
  <b>Customer Financial Analysis | Lending Exposure | Deposit Behavior | Power BI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Banking%20Analytics-1f6feb?style=for-the-badge" alt="Banking Analytics">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-f2c811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Python-Pandas-3776ab?style=for-the-badge&logo=python&logoColor=white" alt="Python and Pandas">
  <img src="https://img.shields.io/badge/Excel-Data%20Validation-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel">
</p>

<p align="center">
  <a href="https://github.com/pranay-125/banking-customer-risk-financial-behavior-analysis">View Repository</a>
  •
  <a href="https://github.com/pranay-125">GitHub Profile</a>
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project analyzes banking customer financial information, including bank loans, business lending, deposits, account balances, credit-card balances, income segments, and customer relationship attributes.
</p>

<p>
Using Python, Pandas, Excel, and Power BI, the project organizes financial data, validates selected figures, examines relationships between numeric variables, and presents portfolio information through a four-page dashboard.
</p>

<p>
The analysis focuses on descriptive financial analytics and lending exposure. Although the project title refers to customer risk, the available analysis does not establish a validated loan-default prediction model or prove that a customer segment has a higher or lower probability of default.
</p>

<hr>

<h2>🎯 Business Objectives</h2>

<ul>
  <li>Examine the distribution of customers across relationship and income segments.</li>
  <li>Analyze bank loans, business lending, deposits, and account balances.</li>
  <li>Explore lending concentration across available customer segments.</li>
  <li>Validate dataset row counts, distinct Client IDs, and selected financial aggregates.</li>
  <li>Use correlation analysis to examine relationships between deposits and account balances.</li>
  <li>Present financial indicators through Power BI dashboard pages and filters.</li>
</ul>

<hr>

<h2>🗂️ Dataset Overview & Validation</h2>

<table>
  <tr>
    <th align="left">Data Check</th>
    <th align="left">Result</th>
  </tr>
  <tr>
    <td>Total dataset rows</td>
    <td><b>3,000</b></td>
  </tr>
  <tr>
    <td>Distinct Client IDs</td>
    <td><b>2,940</b></td>
  </tr>
  <tr>
    <td>Rows beyond the distinct-ID count</td>
    <td><b>60</b></td>
  </tr>
  <tr>
    <td>Exact duplicate rows</td>
    <td>None detected in the reviewed dataset</td>
  </tr>
  <tr>
    <td>Financial attributes</td>
    <td>Income, bank loans, business lending, deposits, account balances, and credit-card balances</td>
  </tr>
  <tr>
    <td>Customer attributes</td>
    <td>Relationship, income-band, demographic, and classification fields</td>
  </tr>
</table>

<p>
<b>Data-quality clarification:</b> The dataset contains 3,000 rows and 2,940 distinct Client IDs. This means that some Client IDs occur more than once. No exact duplicate rows were detected in the reviewed dataset, but repeated Client IDs are not automatically erroneous duplicates and should not be removed without checking their records.
</p>

<p>
The project uses a raw CSV and an organized Excel workbook for data inspection and validation. The reported checks distinguish row counts from unique customer counts.
</p>

<hr>

<h2>🛠️ Tools & Technologies</h2>

<table>
  <tr>
    <th align="left">Tool</th>
    <th align="left">Application in the Project</th>
  </tr>
  <tr>
    <td><b>Python</b></td>
    <td>Data inspection and exploratory analysis</td>
  </tr>
  <tr>
    <td><b>Pandas</b></td>
    <td>Tabular data handling, grouping, and descriptive analysis</td>
  </tr>
  <tr>
    <td><b>Excel</b></td>
    <td>Dataset inspection and validation of selected figures</td>
  </tr>
  <tr>
    <td><b>Power BI</b></td>
    <td>Financial KPI reporting, customer segmentation, and dashboard visualization</td>
  </tr>
</table>

<hr>

<h2>📊 Dashboard Overview</h2>

<p>
The project presents banking portfolio information through four dashboard pages, with filters for relationship, gender, advisor, and time period, as described in the project resume.
</p>

<h3>1. Customer Portfolio & KPI Summary</h3>

<p>
Provides an overview of selected customer and financial indicators, including distinct client count, lending measures, deposit measures, account balances, and customer segments.
</p>

<p align="center">
  <img width="100%" src="https://github.com/user-attachments/assets/7072a1cb-d7d0-4cbf-b0c3-4b0fe6f1134b" alt="Banking customer portfolio and KPI dashboard">
</p>

<h3>2. Loan & Lending Exposure</h3>

<p>
Examines bank loans and business lending, including their distribution across the available income and customer segments. These views describe recorded lending exposure rather than validated default risk.
</p>

<p align="center">
  <img width="100%" src="https://github.com/user-attachments/assets/96e93c94-0583-4b48-ad2e-0aabbc8b5ea7" alt="Banking loan and lending exposure dashboard">
</p>

<h3>3. Deposit & Account Analysis</h3>

<p>
Explores bank deposits and available account-balance measures, including checking, savings, and foreign-currency accounts, across the customer information represented in the dataset.
</p>

<p align="center">
  <img width="100%" src="https://github.com/user-attachments/assets/523b03d8-3732-4ad6-a04d-c46973ed7053" alt="Banking deposit and account analysis dashboard">
</p>

<p>
<i>Dashboard images are illustrative. Financial totals should be interpreted using the definitions and validation limitations documented in this README.</i>
</p>

<hr>

<h2>📈 Key Financial Metrics</h2>

<p>
The following values are based on the reviewed organized dataset. Amounts are expressed in US dollars as represented in the data.
</p>

<table>
  <tr>
    <th align="left">Metric</th>
    <th align="left">Reported Value</th>
    <th align="left">Definition</th>
  </tr>
  <tr>
    <td>Distinct clients</td>
    <td><b>2,940</b></td>
    <td>Count of distinct Client IDs</td>
  </tr>
  <tr>
    <td>Bank loans</td>
    <td><b>~$1.774B</b></td>
    <td>Sum of the Bank Loans field</td>
  </tr>
  <tr>
    <td>Business lending</td>
    <td><b>~$2.600B</b></td>
    <td>Sum of the Business Lending field</td>
  </tr>
  <tr>
    <td>Combined lending measure</td>
    <td><b>~$4.384B</b></td>
    <td>Bank Loans + Business Lending + Credit Card Balance</td>
  </tr>
  <tr>
    <td>Bank deposits</td>
    <td><b>~$2.015B</b></td>
    <td>Sum of the Bank Deposits field</td>
  </tr>
  <tr>
    <td>Checking accounts</td>
    <td><b>~$963.28M</b></td>
    <td>Sum of the Checking Accounts field</td>
  </tr>
  <tr>
    <td>Savings accounts</td>
    <td><b>~$698.73M</b></td>
    <td>Sum of the Saving Accounts field</td>
  </tr>
  <tr>
    <td>Foreign-currency accounts</td>
    <td><b>~$89.65M</b></td>
    <td>Sum of the Foreign Currency Account field</td>
  </tr>
  <tr>
    <td>Combined deposit/account measure</td>
    <td><b>~$3.766B</b></td>
    <td>Bank Deposits + Checking + Savings + Foreign Currency Account</td>
  </tr>
  <tr>
    <td>Credit-card balance</td>
    <td><b>~$9.529M</b></td>
    <td>Sum of the Credit Card Balance field</td>
  </tr>
</table>

<p>
<b>Metric interpretation:</b> The combined lending and deposit/account figures are arithmetic sums of the listed fields. Potential overlap between these measures has not been ruled out. They should therefore be described as combined measures, not assumed to represent unique, non-overlapping financial exposure or customer funds.
</p>

<hr>

<h2>🔎 Lending Concentration Analysis</h2>

<p>
The project resume reports that Private Bank customers accounted for approximately <b>46% of the $1.77B bank loan book</b>. This is a reported portfolio-segmentation finding from the project.
</p>

<p>
The analysis examines lending across relationship, income, and nationality segments. Segment percentages should always be interpreted against the specific lending measure and denominator used in the report.
</p>

<p>
A separate Mid-income segment percentage is not included here because its denominator could not be established clearly from the reviewed documentation. It should be added only after confirming the underlying calculation.
</p>

<hr>

<h2>📉 Correlation Analysis</h2>

<p>
The reviewed dataset showed positive Pearson correlations between bank deposits and selected account-balance fields.
</p>

<table>
  <tr>
    <th align="left">Variable Pair</th>
    <th align="left">Pearson Correlation (r)</th>
    <th align="left">Interpretation</th>
  </tr>
  <tr>
    <td>Bank Deposits and Checking Accounts</td>
    <td><b>~0.84</b></td>
    <td>Strong positive linear association in the reviewed data</td>
  </tr>
  <tr>
    <td>Bank Deposits and Savings Accounts</td>
    <td><b>~0.76</b></td>
    <td>Positive linear association in the reviewed data</td>
  </tr>
</table>

<p>
These correlations describe how the selected numeric variables vary together in this dataset. They do not demonstrate causation, establish customer repayment behavior, or independently validate a credit-risk scoring method.
</p>

<hr>

<h2>🔄 Project Workflow</h2>

<ol>
  <li><b>Data inspection:</b> Reviewed the source CSV and organized Excel workbook.</li>
  <li><b>Data validation:</b> Checked row counts, distinct Client IDs, and selected financial aggregates using Python and Excel.</li>
  <li><b>Data integration:</b> Combined lending and deposit information for the customer portfolio analysis.</li>
  <li><b>Exploratory analysis:</b> Examined financial distributions, customer segments, and selected correlations using Python and Pandas.</li>
  <li><b>Dashboard development:</b> Presented lending, deposit, account-balance, and customer-segment information in Power BI.</li>
  <li><b>Interpretation:</b> Distinguished calculated financial measures from metrics whose business definitions require additional confirmation.</li>
</ol>

<hr>

<h2>⚠️ Limitations & Validation Notes</h2>

<ul>
  <li><b>No validated default outcome:</b> The reviewed dataset does not establish a verified loan-default target for measuring default rates or validating a prediction model.</li>
  <li><b>Risk Weighting:</b> The field contains values on a 1–5 scale, but its meaning and direction have not been independently confirmed. No high-risk or low-risk classification is asserted.</li>
  <li><b>Repeated Client IDs:</b> The dataset has 3,000 rows and 2,940 distinct Client IDs. Repeated identifiers are not automatically treated as exact duplicate rows.</li>
  <li><b>Potential aggregate overlap:</b> Combined lending and deposit/account measures are sums of multiple fields. Their definitions and possible overlap should be checked before treating them as unique portfolio totals.</li>
  <li><b>Fee metric:</b> The dashboard's displayed Total Fees figure could not be independently reproduced from a directly validated monetary fee field in the reviewed organized dataset. It is not presented as verified fee revenue.</li>
  <li><b>Segment percentages:</b> Percentages should be reported only when the denominator and calculation are clear and consistent.</li>
  <li><b>Correlation interpretation:</b> Correlation does not establish causation, default probability, or repayment performance.</li>
</ul>

<hr>

<h2>💡 Project Outcome</h2>

<p>
This project demonstrates a practical banking analytics workflow: examining customer financial information, validating selected figures, analyzing lending concentration, exploring relationships between deposits and account balances, and communicating findings through a Power BI dashboard.
</p>

<p>
The documented outcome is descriptive portfolio analysis and dashboard reporting. No quantified reduction in defaults, improvement in lending decisions, increase in revenue, or predictive credit-risk performance is claimed.
</p>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <b>Pranay Shrivastava</b><br>
  B.Tech in Artificial Intelligence & Data Science, 2026<br>
  <b>Focus:</b> Data Analytics | Business Intelligence | Financial Data Analysis
</p>

<p>
  <a href="mailto:shrivastavapranay.35@gmail.com">Email</a> |
  <a href="https://www.linkedin.com/in/pranayshrivastavaofficial/">LinkedIn</a> |
  <a href="https://github.com/pranay-125">GitHub</a>
</p>

<p align="center">
  <i>Banking Analytics • Data Validation • Exploratory Analysis • Power BI</i>
</p>
```
