![Dashboard1](https://github.com/meghawadhwani20/Credit_Card_Financial_Dashboard/blob/main/Dashboard1.png)
![Dashboard2](https://github.com/meghawadhwani20/Credit_Card_Financial_Dashboard/blob/main/Dashboard2.png)
# Credit Card Financial Dashboard (End-to-End SQL + Power BI Project)

## 1. Project Overview
This end-to-end **Business Intelligence project** explores **credit card customer data** to extract financial insights using **SQL** for data handling and **Power BI** for reporting. Built as a practical case study, the dashboard visualizes key financial metrics like **outstanding balances, delayed payments, credit utilization**, and **customer segmentation**.

## 2. Key Objectives
- **Analyze** the financial health of credit card customers

- **Identify patterns** in delayed payments and outstanding dues

- **Monitor credit usage** and payment behaviors

- **Build** a professional, interactive dashboard for stakeholders

## 3. Project Pipeline
### 3.1 Data Source & Setup
- **Source  :** Credit Card Transaction Dataset (CSV format)

- **Tools Used:** SQL Server or MySQL/PostgreSQL, Power BI

- Created **structured tables** in SQL for querying and analysis

- Connected **Power BI** to the SQL database

### 3.2 Data Modeling & Transformation
- Imported tables into Power BI using **native SQL queries**

- **Cleaned and transformed** data using Power Query

- Built **relationships** between fact and dimension tables

- Created **KPIs and summary metrics** using DAX

### 3.3 Dashboard Design
- **Main Sections in Power BI Dashboard:**

- **Customer Profile Summary:** Age, Gender, Occupation

- **Outstanding & Delayed Payments:** Monthly and user-wise breakdown

- **Credit Utilization:** Percentage usage vs. limit

- **Repayment Behavior:** Trend charts and heatmaps

- **Filters:** Region, Customer Type, Month

- Used slicers, cards, line charts, clustered bar charts, and stacked visuals to present insights clearly.

## 4. Tech Stack
- **SQL Server / MySQL / PostgreSQL :** Data storage and transformations

- **Power BI :** Dashboard development and visualization

- **Power Query :** Data cleaning and shaping

- **DAX:** KPIs and calculated fields

## 5. Results & Insights
- **High Utilization Warning:** 30% of customers use more than 80% of their credit limit

- **Delayed Payments Spike:** Noticeable increase during festive months

- **Segment at Risk:** Young self-employed professionals show the highest overdue rate

- **Payment Patterns:** Most repayments occur between the 25th and 30th of each month

## 6. Project Structure
graphql
Copy
Edit
|-- data/           # Raw and processed data  
|-- sql_scripts/    # SQL scripts for table creation and transformation  
|-- dashboard/      # Power BI (.pbix) file  
|-- README.md       # Project documentation 


## 7. Getting Started
### 7.1 Clone the Repository
bash
Copy
Edit
### 7.2 Set Up SQL Database
Use the SQL scripts provided in the sql_scripts/ folder to **create tables** and **load the data**

### 7.3 Open Power BI Dashboard
Open credit_dashboard.pbix in Power BI

Update and **refresh the connection** to your local SQL database

## 8. Future Enhancements
- Integrate **live SQL connection** for real-time reporting

- Add **machine learning models** to predict customer churn

- Optimize **dashboard view** for mobile devices

