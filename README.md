# Banking Risk Analytics Project

## Objective  
To develop a foundational understanding of **risk analytics** in the banking and financial services domain. The primary goal is to explore how customer-level data can be leveraged to **minimize the risk of loan defaults** and optimize financial decisions while **lending or managing deposits**.

---

## 🔗 Live Dashboard  
Explore the interactive Power BI Dashboard here: [View Banking Risk Analytics Project Dashboard]
<iframe title="Banking_dash_lok" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiNzYyYmQxYTYtOWMwYi00MmI2LTgzZjMtNzEwODZjZTE2ZmI5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9" 

---

## Data Structure  
The project uses a **star schema** consisting of the following tables:

- **Fact Table: `banking_case_customers`**
  - Key Columns: `ClientID`, `BRId`, `Gender`, `IAId`, `Location ID`, `Income Band`, `Age`, `Estimated Income`, `Total Loan`, `Total Deposit`, etc.

- **Dimension Tables:**
  - `banking_case_gender`: Gender details (e.g., `GenderId`, `Gender`)
  - `banking_case_relationship`: Type of bank relationship (e.g., `BRId`, `Banking Relationship`)
  - `banking_case_investment`: Advisor information (e.g., `IAId`, `Investment Advisor`)

---

## Tools Used  
- **Excel** – Initial data inspection and cleaning  
- **Google Colab** – Python-based data exploration  
  - `pandas`, `numpy` – Data handling  
  - `matplotlib`, `seaborn` – Data visualization  
- **SQL** – Data transformation and filtering  
- **Power BI** – Dashboard creation and storytelling

---

## Executive Summary  
- **Private Banks** dominate the banking relationship segment with **46% share** in both **total loans** and **total deposits**.  
- The **Medium Income Band** customers are the **most financially active**, holding over **50% share** in both loan and deposit volumes.  
- **By Occupation**:
  - **VP Sales** has the **highest loan amount**: `$1.44 million`.
  - **Web Developer II** holds the **highest deposit**: `$902,000`.  
- **By Nationality**:
  - **Europeans** hold the largest share of **loans and deposits**, followed by **Asians** and **Australians**, suggesting strong financial engagement.
- **Customer Acquisition**:
  - **21.56%** of new customers joined between **2019 and 2021**, with **2020** showing the **highest spike** in new signups.

---

## Recommendations  
- **Target Medium-Income Groups**: They are the most reliable in terms of both loan uptake and deposit contributions.  
- **Focus on European Segments**: Their financial involvement makes them ideal candidates for upselling financial products.  
- **Analyze Customer Retention for 2020 Cohort**: High acquisition rate in 2020 may indicate effective marketing or product strategy.  
- **Leverage Occupation-Specific Campaigns**: Tailored offers to job roles like **VP Sales** and **Web Developer II** can enhance engagement.  
- **Monitor Private Bank Relationships**: These banks show strong customer participation and could be strategic partners or benchmarks.

---

## Visual Insights  
The interactive Power BI dashboard summarizes key trends across:
- Gender, Nationality, Occupation breakdowns  
- Deposit vs Loan comparisons  
- Time trends in customer onboarding  
- Relationship types and income distribution

file:///C:/Users/Lokesh/Downloads/Banking_dash_lok%20(1).pdf
