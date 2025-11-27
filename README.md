## 📊 Banking Data Analytics Project

## 🧭 Overview

This project demonstrates a complete **end-to-end data analytics workflow** — from loading raw data and performing **Exploratory Data Analysis (EDA)** to creating a **Power BI dashboard** and a **final powerpoint presentation using**.
The goal is to extract meaningful insights from data using **Python, SQL and Power BI**, and to present the findings in a clear, visual, and actionable manner.
We will develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

---

## 📂 Dataset

* **Source:** Kaggle
* **Format:** CSV
* **Size:** Approx. 3000 rows × 25 columns
* **Description:** The dataset contains information about client ID, bank loan, bank deposit, credit card balance, foreign currency account, etc.
* **Key Features:**

  * `Bank Loan` – Loan amount
  * `Bank Deposits` – amount deposited
  * `Savings Accounts` – amount in savings accounts
  * `Foreign Currency Account` – amount in fca
* This dataset basically contains information about bank details ,various client details which consists of multiple tables which are interlinked with each other through keys like primary key and foreign key.
The various tables are Banking Relationship, Client-Banking, Gender, Investment Advisor and Period.

---

## 🛠️ Tools and Technologies

| Category      | Tools Used                                       |
| ------------- | ------------------------------------------------ |
| Programming   | Python (Pandas, NumPy, Matplotlib, Seaborn)      |
| Database      | PostgreSQL / MySQL / SQL Server                  |
| Visualization | Power BI                                         |
| Presentation  | MS Powerpoint                                    |
| Other         | Jupyter Notebook, SQL Workbench / pgAdmin / SSMS |

---

## 🚀 Steps Performed

## 1. Data Loading

* Imported dataset using **Pandas** and **mysql connector**.
* Verified data types and loaded the file into a **DataFrame**.

### 2. Data Cleaning

* Handled **missing values**, **duplicates**, and **inconsistent data**.
* Standardized column names and formats.
* Converted data types where necessary.

### 3. Exploratory Data Analysis (EDA)

* Used **Matplotlib** and **Seaborn** for visual exploration.
* Found patterns, outliers, and correlations.
* Generated statistical summaries.

### 4. Power BI Dashboard

* Connected the cleaned dataset / SQL database to Power BI.
* Created **interactive visuals** showing KPIs, trends.
* Included filters (slicers) for banking relationships, gender, institution advisor, and year of joining.

### 6. Report and Presentation

* Summarized findings and visuals into a **professional report**.
* Built an engaging presentation in **MS POWERPOINT** highlighting:

  * Business problem & objectives
  * Key insights from EDA
  * Visual storytelling through Power BI

---

## 📈 Dashboard

* **Tool:** Microsoft Power BI
* **Main Visuals:**

  * Home Dashboard
  * Loan Analysis
  * Deposit Analysis
  * Summary

---

## 🧾 Results & Insights

* Developed a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
* With our dashboards which are created using Power BI latest tools helps the company to make a decision based on the applicant’s profile like if the applicant is likely to repay the loan then approving the loan otherwise not.

---

## ▶️ How to Run the Project

### Prerequisites

* Python 3.8+
* PostgreSQL / MySQL / SQL Server
* Power BI Desktop
* MS Powerpoint (for final presentation)

### Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/banking-data-analysis.git
   cd data-analytics-project
   ```
2. Install required Python packages:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:

   ```bash
   jupyter notebook Banking_Analysis.ipynb
   ```
4. Import the cleaned dataset into your SQL database.
5. Run SQL queries provided in `queries.sql`.
6. Open the Power BI file (`dashboard.pbix`) to view the dashboard.
7. Review the final presentation via the MS Powerpoint link or PDF.

---

## 🧑‍💻 Author

**Tapan Tiwari**
📧 [tapan.r.tiwari@gmail.com]

---

