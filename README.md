<h1 align="center">🏦 Banking Customer Risk & Financial Behavior Analysis</h1>

<p align="center">
  <b>End-to-End Data Analytics & Business Intelligence Project</b><br>
  Customer Financial Profiling • Lending Exposure • Deposit Analysis • Power BI
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Banking%20Analytics-1f6feb?style=for-the-badge" alt="Banking Analytics">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-f2c811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Python-EDA-3776ab?style=for-the-badge&logo=python&logoColor=white" alt="Python EDA">
  <img src="https://img.shields.io/badge/Excel-Data%20Preparation-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel">
</p>

<p align="center">
  <a href="https://github.com/pranay-125/banking-customer-risk-financial-behavior-analysis">View Repository</a>
  •
  <a href="https://github.com/pranay-125">GitHub Profile</a>
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project explores banking customer financial profiles, lending exposure, deposit balances, account holdings, income segments, and customer relationship information using Python-based exploratory data analysis (EDA), Excel, and Power BI.
</p>

<p>
The objective is to organize customer-level financial data into measurable portfolio indicators and interactive dashboard views that help users examine the distribution of lending, deposits, account balances, and customer segments.
</p>

<p>
The project focuses on <b>descriptive analytics and financial exposure analysis</b>. The available dataset does not provide a validated loan-default outcome, so the analysis does not claim to predict defaults, establish repayment performance, or prove that a particular customer segment is safer to lend to.
</p>

<hr>

<h2>🎯 Business Problem</h2>

<p>
Banking datasets contain multiple financial measures and customer attributes that can be difficult to assess in isolation. This project structures those measures into a dashboard to help explore the following questions:
</p>

<ul>
  <li>How is the customer portfolio distributed across income and relationship segments?</li>
  <li>What is the recorded value of bank loans and business lending?</li>
  <li>How are bank deposits distributed alongside checking, savings, and foreign-currency account balances?</li>
  <li>How do credit-card balances and other financial measures vary across the available customer data?</li>
  <li>What descriptive relationships exist between selected financial variables?</li>
  <li>How can KPI cards, charts, and filters make portfolio information easier to explore?</li>
</ul>

<hr>

<h2>🗂️ Dataset Overview</h2>

<table>
  <tr>
    <th align="left">Data Attribute</th>
    <th align="left">Validated Information</th>
  </tr>
  <tr>
    <td>Main dataset records</td>
    <td>3,000 rows</td>
  </tr>
  <tr>
    <td>Distinct Client IDs</td>
    <td>2,940</td>
  </tr>
  <tr>
    <td>Repeated Client IDs</td>
    <td>60 records beyond the distinct-ID count</td>
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
    <td>Demographic, income-band, relationship, and classification fields</td>
  </tr>
</table>

<p>
<b>Data-quality note:</b> The dataset contains 3,000 rows but only 2,940 distinct Client IDs. Repeated IDs should not automatically be treated as erroneous duplicates because the records may contain differing values. The distinction between row counts and distinct customer counts is important when interpreting portfolio KPIs.
</p>

<p>
The project files include a raw CSV and an organized Excel workbook. The organized workbook was used to validate selected aggregate financial figures against the dashboard.
</p>

<hr>

<h2>🛠️ Tools & Technologies</h2>

<table>
  <tr>
    <th align="left">Tool</th>
    <th align="left">Project Application</th>
  </tr>
  <tr>
    <td><b>Python</b></td>
    <td>Exploratory data analysis and statistical inspection</td>
  </tr>
  <tr>
    <td><b>Pandas</b></td>
    <td>Tabular data handling, grouping, and descriptive analysis</td>
  </tr>
  <tr>
    <td><b>NumPy</b></td>
    <td>Numerical analysis</td>
  </tr>
  <tr>
    <td><b>Jupyter Notebook</b></td>
    <td>Documenting and exploring the analytical workflow</td>
  </tr>
  <tr>
    <td><b>Microsoft Excel</b></td>
    <td>Organized dataset inspection and aggregate validation</td>
  </tr>
  <tr>
    <td><b>Power BI</b></td>
    <td>Portfolio KPI cards, financial analysis visuals, and interactive reporting</td>
  </tr>
  <tr>
    <td><b>DAX</b></td>
    <td>Dashboard measures and aggregations, subject to the definitions implemented in the PBIX file</td>
  </tr>
</table>

<hr>

<h2>📊 Dashboard Preview</h2>

<p>
The Power BI dashboard presents an executive summary of banking portfolio measures alongside dedicated loan and deposit analysis views. The screenshots below illustrate the project's dashboard layout.
</p>

<h3>1. 🧭 Customer Portfolio & KPI Summary</h3>

<table>
  <tr>
    <td width="55%" valign="top">
      <img width="100%" src="https://github.com/user-attachments/assets/7072a1cb-d7d0-4cbf-b0c3-4b0fe6f1134b" alt="Banking customer portfolio and KPI dashboard">
    </td>
    <td width="45%" valign="top">
      <b>Dashboard coverage</b>
      <ul>
        <li>Distinct client count</li>
        <li>Combined lending exposure</li>
        <li>Bank loans and business lending</li>
        <li>Deposit and account-balance measures</li>
        <li>Credit-card balance and customer segmentation</li>
      </ul>
      <b>Purpose</b>
      <p>Provides a consolidated view of selected portfolio measures and helps users navigate the main financial indicators.</p>
    </td>
  </tr>
</table>

<h3>2. 💳 Loan & Lending Exposure Analysis</h3>

<table>
  <tr>
    <td width="45%" valign="top">
      <b>Dashboard coverage</b>
      <ul>
        <li>Bank loan exposure</li>
        <li>Business lending</li>
        <li>Combined lending measure</li>
        <li>Loan distribution across income bands</li>
      </ul>
      <b>Analytical purpose</b>
      <p>Examines how recorded lending values are distributed across available portfolio segments. This is descriptive exposure analysis, not a validated assessment of default probability.</p>
    </td>
    <td width="55%" valign="top">
      <img width="100%" src="https://github.com/user-attachments/assets/96e93c94-0583-4b48-ad2e-0aabbc8b5ea7" alt="Banking loan and lending exposure analysis dashboard">
    </td>
  </tr>
</table>

<h3>3. 📈 Deposit & Account Analysis</h3>

<table>
  <tr>
    <td width="55%" valign="top">
      <img width="100%" src="https://github.com/user-attachments/assets/523b03d8-3732-4ad6-a04d-c46973ed7053" alt="Banking deposit and account analysis dashboard">
    </td>
    <td width="45%" valign="top">
      <b>Dashboard coverage</b>
      <ul>
        <li>Bank deposits</li>
        <li>Checking account balances</li>
        <li>Savings account balances</li>
        <li>Foreign-currency account balances</li>
        <li>Deposit distribution by customer relationship segment</li>
      </ul>
      <b>Analytical purpose</b>
      <p>Compares recorded deposit and account measures to explore their distribution across the available customer segments.</p>
    </td>
  </tr>
</table>

<p>
<i>Dashboard screenshots are illustrative views of the report. Values displayed in the report should be interpreted using the metric definitions and validation notes documented below.</i>
</p>

<hr>

<h2>📌 Key Quantified Portfolio Metrics</h2>

<p>
The following figures were checked against the organized Excel data and/or the dashboard values previously reviewed. Currency amounts are expressed in US dollars, as represented in the dataset.
</p>

<table>
  <tr>
    <th align="left">Metric</th>
    <th align="left">Value</th>
    <th align="left">Interpretation</th>
  </tr>
  <tr>
    <td>Dataset rows</td>
    <td><b>3,000</b></td>
    <td>Records in the reviewed main customer dataset</td>
  </tr>
  <tr>
    <td>Distinct Client IDs</td>
    <td><b>2,940</b></td>
    <td>Unique client identifiers in the reviewed data</td>
  </tr>
  <tr>
    <td>Bank Loans</td>
    <td><b>~$1.774 billion</b></td>
    <td>Sum of the Bank Loans field</td>
  </tr>
  <tr>
    <td>Business Lending</td>
    <td><b>~$2.600 billion</b></td>
    <td>Sum of the Business Lending field</td>
  </tr>
  <tr>
    <td>Combined lending measure</td>
    <td><b>~$4.384 billion</b></td>
    <td>Bank Loans + Business Lending + Credit Card Balance</td>
  </tr>
  <tr>
    <td>Bank Deposits</td>
    <td><b>~$2.015 billion</b></td>
    <td>Sum of the Bank Deposits field</td>
  </tr>
  <tr>
    <td>Checking Accounts</td>
    <td><b>~$963.28 million</b></td>
    <td>Sum of the Checking Accounts field</td>
  </tr>
  <tr>
    <td>Saving Accounts</td>
    <td><b>~$698.73 million</b></td>
    <td>Sum of the Saving Accounts field</td>
  </tr>
  <tr>
    <td>Foreign Currency Account</td>
    <td><b>~$89.65 million</b></td>
    <td>Sum of the Foreign Currency Account field</td>
  </tr>
  <tr>
    <td>Combined deposit/account measure</td>
    <td><b>~$3.766 billion</b></td>
    <td>Bank Deposits + Checking + Savings + Foreign Currency Account</td>
  </tr>
  <tr>
    <td>Credit Card Balance</td>
    <td><b>~$9.529 million</b></td>
    <td>Sum of the Credit Card Balance field</td>
  </tr>
</table>

<p>
<b>Important:</b> The combined lending and deposit/account figures are arithmetic aggregates of the listed fields. They should not automatically be interpreted as unique, non-overlapping exposures or customer funds until the business definitions and potential overlap between fields have been confirmed.
</p>

<hr>

<h2>🔎 Descriptive Analysis & Relationships</h2>

<p>
The reviewed organized dataset showed the following Pearson correlations between selected numeric fields:
</p>

<table>
  <tr>
    <th align="left">Variable Pair</th>
    <th align="left">Pearson Correlation (r)</th>
    <th align="left">What It Indicates</th>
  </tr>
  <tr>
    <td>Bank Deposits and Checking Accounts</td>
    <td><b>~0.844</b></td>
    <td>Strong positive linear association in the reviewed data</td>
  </tr>
  <tr>
    <td>Bank Deposits and Saving Accounts</td>
    <td><b>~0.755</b></td>
    <td>Positive linear association in the reviewed data</td>
  </tr>
  <tr>
    <td>Estimated Income and Risk Weighting</td>
    <td><b>~0.665</b></td>
    <td>Positive association; interpretation depends on the meaning and direction of Risk Weighting</td>
  </tr>
  <tr>
    <td>Bank Loans and Business Lending</td>
    <td><b>~0.417</b></td>
    <td>Moderate positive linear association in the reviewed data</td>
  </tr>
  <tr>
    <td>Credit Card Balance and Risk Weighting</td>
    <td><b>~0.400</b></td>
    <td>Positive association; not sufficient to establish credit-default risk</td>
  </tr>
</table>

<p>
These coefficients describe relationships between variables in this dataset. They do not establish causation, prove repayment outcomes, or independently validate a credit-risk scoring rule.
</p>

<hr>

<h2>🧮 KPI Definitions & Validation Notes</h2>

<table>
  <tr>
    <th align="left">Dashboard KPI</th>
    <th align="left">Definition / Validation Status</th>
  </tr>
  <tr>
    <td>Total Clients</td>
    <td>Dashboard shows 2,940 distinct clients. The main dataset contains 3,000 rows and 2,940 distinct Client IDs.</td>
  </tr>
  <tr>
    <td>Total Loan</td>
    <td>Approximately $4.384 billion using Bank Loans + Business Lending + Credit Card Balance. Confirm that this is the intended business definition in the Power BI model.</td>
  </tr>
  <tr>
    <td>Total Deposit</td>
    <td>Approximately $3.766 billion when Bank Deposits, Checking Accounts, Saving Accounts, and Foreign Currency Account are added together. Possible overlap between these fields has not been ruled out.</td>
  </tr>
  <tr>
    <td>Total Fees</td>
    <td>The dashboard displays approximately $158.19 million, but the organized dataset contains a categorical Fee Structure field rather than a directly validated monetary fee amount. This figure is therefore not presented as an independently verified revenue result.</td>
  </tr>
  <tr>
    <td>Engagement Days / Duration</td>
    <td>Used to explore customer relationship information. Do not interpret relationship duration as proof of repayment performance or lower default risk.</td>
  </tr>
  <tr>
    <td>Credit Card Balance</td>
    <td>Approximately $9.529 million from the source field. This is a balance measure, not a validated credit-utilization percentage.</td>
  </tr>
  <tr>
    <td>Risk Weighting</td>
    <td>The source contains values on a 1–5 scale, but the score's direction and business definition have not been independently confirmed. No high-risk/low-risk interpretation is asserted.</td>
  </tr>
</table>

<hr>

<h2>🔄 Project Workflow</h2>

<ol>
  <li><b>Data inspection:</b> Reviewed the raw CSV and organized Excel workbook.</li>
  <li><b>Data validation:</b> Checked row counts, distinct client identifiers, and selected financial aggregates.</li>
  <li><b>Exploratory data analysis:</b> Examined numerical summaries, distributions, customer segments, and selected correlations.</li>
  <li><b>Financial analysis:</b> Compared lending measures, deposit measures, account balances, and credit-card balances.</li>
  <li><b>Dashboard reporting:</b> Presented portfolio measures and segment-level views in Power BI.</li>
  <li><b>Interpretation:</b> Distinguished directly calculated results from dashboard measures that still require business-definition validation.</li>
</ol>

<hr>

<h2>📄 Project Documentation</h2>

<p>The repository contains supporting project documentation, including:</p>

<ul>
  <li><b>Business Requirements Document:</b> Project objectives, scope, and KPI requirements.</li>
  <li><b>Domain Knowledge Document:</b> Banking terminology and domain context.</li>
  <li><b>Dashboard Insights Report:</b> A summary of dashboard views and intended interpretations.</li>
  <li><b>EDA notebooks and exports:</b> Python-based exploratory analysis artifacts.</li>
  <li><b>Power BI report:</b> The interactive dashboard file.</li>
</ul>

<p>
Documentation that discusses default risk, repayment stability, or fee revenue should be read in light of the validation limitations stated in this README. Those outcomes have not been independently established by the reviewed dataset.
</p>

<hr>

<h2>⚠️ Data Limitations & Analytical Boundaries</h2>

<ul>
  <li><b>No validated default target:</b> The reviewed data does not provide a verified loan-default outcome suitable for calculating a default rate or validating a default prediction.</li>
  <li><b>Risk Weighting semantics:</b> The meaning and direction of the 1–5 values require confirmation before using them as a risk ranking.</li>
  <li><b>Repeated identifiers:</b> There are 3,000 rows and 2,940 distinct Client IDs. Repeated IDs were not automatically removed.</li>
  <li><b>Aggregate overlap:</b> The combined lending and deposit/account measures are sums of multiple fields. Potential overlap must be checked before treating them as unique portfolio totals.</li>
  <li><b>Fee calculation:</b> The dashboard's displayed Total Fees figure could not be independently reproduced from a directly available monetary fee field in the organized dataset.</li>
  <li><b>Income-band definitions:</b> Band thresholds and labels should be kept consistent between the notebook, organized data, and Power BI report.</li>
  <li><b>Descriptive correlations:</b> Correlation values do not prove causal relationships or repayment outcomes.</li>
  <li><b>Reproducibility:</b> Notebook source paths and date-parsing assumptions require verification before claiming that the notebook runs successfully from a fresh clone.</li>
</ul>

<hr>

<h2>💡 Project Outcome</h2>

<p>
This project demonstrates a practical analytics workflow for examining a banking customer portfolio, validating financial aggregates, investigating relationships between numeric variables, and presenting selected indicators through Power BI.
</p>

<p>
The key deliverable is a descriptive portfolio dashboard supported by data exploration. The project does not claim measured reductions in defaults, improved lending approvals, increased revenue, or other quantified business outcomes.
</p>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <b>Pranay Shrivastava</b><br>
  B.Tech – Artificial Intelligence & Data Science<br>
  <b>Specialization:</b> Data Analytics | Business Intelligence
</p>

<p>
  <a href="mailto:shrivastavapranay.35@gmail.com">Email</a> |
  <a href="https://www.linkedin.com/in/pranayshrivastavaofficial/">LinkedIn</a> |
  <a href="https://github.com/pranay-125">GitHub</a>
</p>

<p align="center">
  <i>Banking Analytics • Exploratory Data Analysis • Power BI • Financial Data Validation</i>
</p>
