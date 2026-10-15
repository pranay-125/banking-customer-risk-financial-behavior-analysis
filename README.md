
<h1 align="center">🏦 Banking Customer Risk & Financial Behavior Analysis</h1>

<p align="center">
  <b>Customer Portfolio Analytics • Lending Exposure • Deposit Analysis • Business Intelligence</b><br>
  An exploratory data analysis and Power BI dashboard project
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Banking%20Analytics-1f6feb?style=for-the-badge" alt="Banking Analytics">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-f2c811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Python-Pandas%20EDA-3776ab?style=for-the-badge&logo=python&logoColor=white" alt="Python and Pandas">
  <img src="https://img.shields.io/badge/Excel-Data%20Validation-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel">
</p>

<p align="center">
  <a href="https://github.com/pranay-125/banking-customer-risk-financial-behavior-analysis">View Repository</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/pranay-125">GitHub Profile</a>
  &nbsp;•&nbsp;
  <a href="https://www.linkedin.com/in/pranayshrivastavaofficial/">LinkedIn</a>
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
  This project analyzes banking customer financial information, including bank loans, business lending, deposits, account balances, credit-card balances, income segments, and customer relationship attributes.
</p>

<p>
  Using Python-based exploratory data analysis, Pandas, Excel, and Power BI, the project organizes financial measures into portfolio-level indicators and dashboard views. The goal is to make lending exposure, deposit distribution, and customer segments easier to examine through structured reporting and data visualization.
</p>

<p>
  <b>Analytical scope:</b> This is a descriptive banking analytics project. It explores financial patterns and portfolio exposure; it does not claim to predict loan defaults or validate a credit-risk scoring model.
</p>

<hr>

<h2>🎯 Business Problem</h2>

<p>
  Banking data contains multiple financial measures and customer attributes that are difficult to interpret when viewed separately. A consolidated analytical view helps organize these measures and investigate questions such as:
</p>

<ul>
  <li>How is the customer portfolio distributed across available income and relationship segments?</li>
  <li>What is the recorded value of bank loans and business lending?</li>
  <li>How are bank deposits distributed alongside checking, savings, and foreign-currency account balances?</li>
  <li>How do lending and deposit measures vary across customer segments?</li>
  <li>What descriptive relationships exist between selected financial variables?</li>
  <li>How can KPI cards, charts, and dashboard filters improve access to portfolio information?</li>
</ul>

<hr>

<h2>🗂️ Dataset Overview</h2>

<table>
  <tr>
    <th align="left">Data Attribute</th>
    <th align="left">Reviewed Information</th>
  </tr>
  <tr>
    <td>Main dataset rows</td>
    <td>3,000</td>
  </tr>
  <tr>
    <td>Distinct Client IDs</td>
    <td>2,940</td>
  </tr>
  <tr>
    <td>Rows beyond the distinct-ID count</td>
    <td>60</td>
  </tr>
  <tr>
    <td>Exact duplicate rows</td>
    <td>None detected in the reviewed dataset</td>
  </tr>
  <tr>
    <td>Financial attributes</td>
    <td>Income, bank loans, business lending, bank deposits, account balances, and credit-card balances</td>
  </tr>
  <tr>
    <td>Customer attributes</td>
    <td>Income band, customer relationship, demographic, and classification fields</td>
  </tr>
</table>

<p>
  <b>Data-quality consideration:</b> The dataset contains 3,000 rows and 2,940 distinct Client IDs. Repeated identifiers are not automatically errors: records must be checked before deciding whether they represent duplicate customers, multiple observations, or inconsistent records. The figures above distinguish the row count from the distinct-ID count.
</p>

<p>
  The analysis uses the organized Excel workbook and associated project data to inspect records and validate selected aggregate financial values. Aggregate figures should be interpreted according to their underlying field definitions.
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
    <td>Exploration and documentation of the analytical workflow</td>
  </tr>
  <tr>
    <td><b>Microsoft Excel</b></td>
    <td>Dataset inspection and validation of selected aggregate values</td>
  </tr>
  <tr>
    <td><b>Power BI</b></td>
    <td>Portfolio KPI reporting, financial analysis visuals, and customer-segment views</td>
  </tr>
  <tr>
    <td><b>DAX</b></td>
    <td>Power BI measures, subject to the definitions implemented in the report</td>
  </tr>
</table>

<hr>

<h2>📊 Dashboard Preview</h2>

<p>
  The dashboard is organized around customer portfolio indicators, lending exposure, and deposit/account analysis. The following screenshots illustrate the report views included in the original project README.
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
        <li>Lending exposure indicators</li>
        <li>Bank loans and business lending</li>
        <li>Deposit and account-balance measures</li>
        <li>Credit-card balances and customer segmentation</li>
      </ul>
      <b>Purpose</b>
      <p>
        Consolidates selected portfolio measures to support an overview of the available banking customer data.
      </p>
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
        <li>Lending distribution across income segments</li>
      </ul>
      <b>Analytical purpose</b>
      <p>
        Examines the distribution of recorded lending values across available portfolio segments. The results describe exposure in the dataset rather than verified default probability or repayment performance.
      </p>
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
        <li>Deposit distribution across customer relationship segments</li>
      </ul>
      <b>Analytical purpose</b>
      <p>
        Compares recorded deposit and account measures to explore their distribution across the available customer data.
      </p>
    </td>
  </tr>
</table>

<p>
  <i>Note: Screenshots illustrate the report layout. Combined totals should be interpreted using the field definitions and validation notes below.</i>
</p>

<hr>

<h2>📌 Key Quantified Portfolio Metrics</h2>

<p>
  The following figures are based on the reviewed project data and selected aggregate calculations. Currency amounts are expressed in US dollars as represented in the dataset.
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
    <td>Records in the reviewed main dataset</td>
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
    <td>Savings Accounts</td>
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
    <td>Bank Deposits + Checking Accounts + Saving Accounts + Foreign Currency Account</td>
  </tr>
  <tr>
    <td>Credit Card Balance</td>
    <td><b>~$9.529 million</b></td>
    <td>Sum of the Credit Card Balance field</td>
  </tr>
</table>

<p>
  <b>Interpretation note:</b> The combined lending and deposit/account measures are arithmetic sums of the listed fields. The fields may overlap in business meaning. Therefore, these calculations should not automatically be interpreted as unique, non-overlapping exposures or as separate funds without confirming the data definitions.
</p>

<hr>

<h2>🔎 Descriptive Analysis & Relationships</h2>

<p>
  The reviewed organized dataset showed the following Pearson correlations between selected numerical fields:
</p>

<table>
  <tr>
    <th align="left">Variable Pair</th>
    <th align="left">Pearson Correlation (r)</th>
    <th align="left">Interpretation</th>
  </tr>
  <tr>
    <td>Bank Deposits and Checking Accounts</td>
    <td><b>~0.844</b></td>
    <td>Strong positive linear association in the reviewed data</td>
  </tr>
  <tr>
    <td>Bank Deposits and Savings Accounts</td>
    <td><b>~0.755</b></td>
    <td>Positive linear association in the reviewed data</td>
  </tr>
  <tr>
    <td>Estimated Income and Risk Weighting</td>
    <td><b>~0.665</b></td>
    <td>Positive association; interpretation depends on the meaning of Risk Weighting</td>
  </tr>
  <tr>
    <td>Bank Loans and Business Lending</td>
    <td><b>~0.417</b></td>
    <td>Moderate positive linear association in the reviewed data</td>
  </tr>
  <tr>
    <td>Credit Card Balance and Risk Weighting</td>
    <td><b>~0.400</b></td>
    <td>Positive association; not sufficient to establish default risk</td>
  </tr>
</table>

<p>
  These coefficients describe linear associations in the reviewed dataset. Correlation does not establish causation, repayment outcomes, or the predictive validity of a credit-risk rule. In particular, the meaning and direction of the Risk Weighting field must be confirmed before interpreting it as a risk ranking.
</p>

<hr>

<h2>🧮 KPI Definitions & Validation Notes</h2>

<table>
  <tr>
    <th align="left">Metric / Field</th>
    <th align="left">Definition and Validation Status</th>
  </tr>
  <tr>
    <td>Total Clients</td>
    <td>2,940 distinct Client IDs in a dataset containing 3,000 rows.</td>
  </tr>
  <tr>
    <td>Total Loan / Combined Lending</td>
    <td>Approximately $4.384 billion when Bank Loans, Business Lending, and Credit Card Balance are added together. This is a calculated aggregate; confirm that it matches the intended business definition.</td>
  </tr>
  <tr>
    <td>Total Deposit / Combined Deposit-Account Measure</td>
    <td>Approximately $3.766 billion when Bank Deposits, Checking Accounts, Saving Accounts, and Foreign Currency Account are added together. Potential overlap between fields has not been ruled out.</td>
  </tr>
  <tr>
    <td>Total Fees</td>
    <td>The dashboard displays approximately $158.19 million, but a directly validated monetary fee field was not established in the reviewed organized dataset. This figure is not presented as a verified fee-revenue result.</td>
  </tr>
  <tr>
    <td>Engagement Days / Duration</td>
    <td>Can be used to explore customer relationship information. Duration alone does not prove repayment performance or lower default risk.</td>
  </tr>
  <tr>
    <td>Credit Card Balance</td>
    <td>Approximately $9.529 million from the source field. This is a balance measure, not a validated credit-utilization percentage.</td>
  </tr>
  <tr>
    <td>Risk Weighting</td>
    <td>The source contains values on a 1–5 scale, but the score's direction and business definition have not been independently confirmed. No high-risk or low-risk classification is asserted.</td>
  </tr>
</table>

<hr>

<h2>🔄 Project Workflow</h2>

<ol>
  <li><b>Data inspection:</b> Reviewed the raw CSV and organized Excel workbook.</li>
  <li><b>Data validation:</b> Checked dataset row counts, distinct Client IDs, and selected financial aggregates.</li>
  <li><b>Exploratory data analysis:</b> Examined numerical summaries, distributions, customer segments, and selected correlations.</li>
  <li><b>Financial analysis:</b> Compared lending measures, deposit measures, account balances, and credit-card balances.</li>
  <li><b>Dashboard reporting:</b> Presented portfolio indicators and segment-level views in Power BI.</li>
  <li><b>Interpretation:</b> Distinguished calculated descriptive results from measures that require additional business-definition validation.</li>
</ol>

<hr>

<h2>📄 Project Documentation</h2>

<p>
  The repository includes supporting materials for the analytical project, such as:
</p>

<ul>
  <li><b>Business Requirements Document:</b> Project objectives, scope, and KPI requirements.</li>
  <li><b>Domain Knowledge Document:</b> Banking terminology and domain context.</li>
  <li><b>Dashboard Insights Report:</b> A summary of dashboard views and their intended interpretation.</li>
  <li><b>EDA notebooks and data files:</b> Supporting materials for exploratory analysis.</li>
  <li><b>Power BI report:</b> Dashboard reporting artifact.</li>
</ul>

<p>
  Any documentation discussing default risk, repayment stability, or fee revenue should be interpreted alongside the limitations described in this README. These outcomes have not been independently established by the reviewed data.
</p>

<hr>

<h2>⚠️ Data Limitations & Analytical Boundaries</h2>

<ul>
  <li><b>No validated default outcome:</b> The reviewed dataset does not provide a verified loan-default outcome for calculating a default rate or validating default predictions.</li>
  <li><b>Risk Weighting definition:</b> The meaning and direction of the 1–5 values require confirmation before using them as a risk ranking.</li>
  <li><b>Repeated identifiers:</b> There are 3,000 rows and 2,940 distinct Client IDs. Repeated IDs were not automatically removed or treated as erroneous duplicates.</li>
  <li><b>Aggregate overlap:</b> Combined lending and deposit/account measures are sums of multiple fields. Potential overlap must be checked before interpreting them as unique portfolio totals.</li>
  <li><b>Fee calculation:</b> The dashboard's displayed Total Fees figure could not be independently reproduced from a directly validated monetary fee field in the reviewed organized dataset.</li>
  <li><b>Income-band definitions:</b> Band thresholds and labels should remain consistent across the notebook, organized data, and Power BI report.</li>
  <li><b>Correlation limits:</b> Correlation coefficients do not prove causality, repayment outcomes, or credit-default risk.</li>
  <li><b>Reproducibility:</b> Notebook paths and date-parsing assumptions should be checked before claiming that the workflow runs successfully from a fresh repository clone.</li>
</ul>

<hr>

<h2>💡 Project Outcome</h2>

<p>
  This project demonstrates a practical banking analytics workflow: inspecting customer-level financial data, validating selected aggregates, exploring relationships between numerical variables, segmenting portfolio measures, and presenting descriptive indicators through Power BI.
</p>

<p>
  The primary deliverable is a portfolio dashboard supported by exploratory analysis. The project does not claim measured reductions in defaults, improved lending approvals, increased revenue, or validated credit-risk predictions.
</p>

<hr>

<h2>👨‍💻 Author</h2>

<p>
  <b>Pranay Shrivastava</b><br>
  B.Tech – Artificial Intelligence & Data Science, 2026<br>
  <b>Focus:</b> Data Analytics | Business Intelligence | Dashboard Development
</p>

<p>
  <a href="mailto:shrivastavapranay.35@gmail.com">Email</a>
  &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/pranayshrivastavaofficial/">LinkedIn</a>
  &nbsp;|&nbsp;
  <a href="https://github.com/pranay-125">GitHub</a>
</p>

<p align="center">
  <i>Banking Analytics • Python • Pandas • Excel • Power BI • Financial Data Validation</i>
</p>
