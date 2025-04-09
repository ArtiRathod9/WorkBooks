# 📚 Data Skills Bootcamp - Just IT

##  🛠️ Tools Learn

- 📊 **Excel** – Spreadsheets, formulas, pivot tables , VLOOKUP/XLOOKUP
- 📈 **Power BI** –Power Query, DAX and Data Dashboards
- 📉 **Tableau** – Visual analytics and interactive dashboards
- 🛢️ **SQL** – Structured Query Language for databases
- ☁️ **Microsoft Azure** – Cloud computing and data services
- 🐍 **Python** – Data analysis, scripting, and automation, Pandas, Matplotlib , Seaborn
---

### 🚀 Data Skills Bootcamp – Overview
- The Data Skills Bootcamp is an intensive, hands-on training program designed to build real-world data capabilities through practical exercises and project-based learning. Participants will gain experience with leading data visualization and analysis tools including Power BI, Tableau, Python, SQL, and Excel.
- Areas covered on bootcamp like what is Data/Big Data, Data cleaning, Analysis,Visualisation, interactive dashboards, Cloud Services, GDPR & Data Ethics, SQL Queries, Python Scripting.
---
## 📆💻 Weekly Training and Tools learn
#### 📘 Week 1: Excel Essentials, Data Analysis Foundations, DPA & GDPR
- Topics Covered: Data handling in Excel, key functions, PivotTables, VLOOKUP, and chart creation.
#### 📊 Week 2: Power BI & Tableau Dashboards
- Projects: Spotify Listening Trends Dashboard (Power BI) & NHS Healthcare Insights Dashboard (Tableau)
- Focus: Data visualization, interactive dashboards, storytelling with data
#### 🛢️ Week 3: Relational Databases & SQL Fundamentals
- Topics Covered: Database concepts, table relationships, writing SQL queries for data extraction, filtering, joining, and aggregation.
#### ☁️ Week 5: Introduction to Microsoft Azure for Data
- Topics Covered: Cloud computing fundamentals, data storage solutions
#### 🐍 Week 6: Python for Data Analysis & Visualization
- Topics Covered:
- Data manipulation with pandas , Data visualization using Matplotlib and Seaborn, Exploratory Data Analysis (EDA) and basic charting techniques
---
## 📊📘 Visualizations by Weekly Workbook
---
### Week 1 - Excel Functions , Pivot Table , Vlookup
#### Excel functions
![Excel Function](Visualisation/exlfn.png)
#### Vlookup and Xlookup formulas and output
 ![Vlookup](Visualisation/vlkp.png)
 
 ![Xlookup](Visualisation/xlkp.png)
 
 ![Output](Visualisation/vxlkp.png)
#### Pivot Table and bar Chart
 ![Pivot Table](Visualisation/pvt.png)
#### Switch Function
 ![Switch](Visualisation/swt.png)
---
## Week 2 Tableau and Data Visualisation
#### Tableau Dashboard
#### PowerBI Dashboard
![powerBi](Visualisation/advn.png)
---
## Week 3 Relational Database & SQL Queries
### 🔗 SQL Joins Reference
#### ✅ **INNER JOIN**
Returns only matching rows between both tables.
```sql
SELECT Customers.name, Orders.product
FROM Customers
INNER JOIN Orders ON Customers.customer_id = Orders.customer_id;
```
---
####👈 **LEFT JOIN**
Returns all records from the left table, and matched records from the right.
```sql
SELECT Customers.name, Orders.product
FROM Customers
LEFT JOIN Orders ON Customers.customer_id = Orders.customer_id;
```
---
#### 👉 **RIGHT JOIN**
Returns all records from the right table, and matched records from the left.
```sql
SELECT Customers.name, Orders.product
FROM Customers
RIGHT JOIN Orders ON Customers.customer_id = Orders.customer_id;
```
---
#### 🔄 **FULL OUTER JOIN**
Returns all records when there is a match in either left or right table.
```sql
SELECT Customers.name, Orders.product
FROM Customers
FULL OUTER JOIN Orders ON Customers.customer_id = Orders.customer_id;
```
---
#### 🔁 **SELF JOIN**
Joins a table with itself. Useful for hierarchical data (e.g., employees & managers).
```sql
SELECT 
    e.name AS employee,
    m.name AS manager
FROM Employees e
LEFT JOIN Employees m ON e.manager_id = m.employee_id;

