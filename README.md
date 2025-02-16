# Sales Analysis using SQL & Power BI

## 📌 Project Overview
This project focuses on improving sales reporting by transitioning from static reports to interactive Power BI dashboards. The analysis is based on the AdventureWorksDW2019 database, with data extracted, cleaned, and transformed using SQL before visualizing key insights in Power BI.

## 🎯 Project Goals
### What I Wanted to Do:
- Improve sales reporting by creating dynamic dashboards.
- Analyze sales trends over time.
- Identify top-selling products and key customers.
- Compare actual sales performance with budgeted targets.
- Enable filtering by salesperson, product, and customer.

### What I Did:
1. **Restored Database**: Loaded AdventureWorksDW2019_DatesUpdated.bak into SQL Server.
2. **Extracted & Cleaned Data**: Used SQL scripts to extract required tables:
   - DIM_Product
   - DIM_Calendar
   - DIM_Customer
   - FACT_InternetSales
3. **Saved Cleaned Data**:
   - Exported query results to CSV format.
4. **Loaded Data into Power BI**:
   - Connected CSV files to Power BI.
   - Created relationships between tables.
5. **Built Three Dashboards**:
   - **Sales Overview**
   - **Product Overview**
   - **Customer Overview**

## 📂 Project Structure
Sales-Analysis-PowerBI/
├── Database_Backup/
│   ├── AdventureWorksDW2019_DatesUpdated.bak
├── SQL_Scripts/
│   ├── DIM_Product.sql
│   ├── DIM_Calendar.sql
│   ├── DIM_Customer.sql
│   ├── FACT_InternetSales.sql
├── Cleaned_Data_CSVs/
│   ├── DIM_Product.csv
│   ├── DIM_Calendar.csv
│   ├── DIM_Customer.csv
│   ├── FACT_InternetSales.csv
├── PowerBI_Dashboard/
│   ├── Sales_Report_Dashboard.pbix
│   ├── Screenshots/
│   │   ├── Sales_Overview.png
│   │   ├── Product_Overview.png
│   │   ├── Customer_Overview.png
├── README.md

## 📂 Database Download  
To restore the database, download the backup file from Google Drive:  

🔗 **[AdventureWorksDW2019 Database Backup](https://drive.google.com/file/d/1SIzH187Vg356D1FdBkFn1TLPuNW2y-Uu/view?usp=drive_link)**  


## 📊 Dashboards & Insights
### 1️⃣ Sales Overview
- Displays total revenue, sales trends, and budget comparison.
- Shows performance metrics over time.

![Sales Overview](https://github.com/muhammed-saheer/Sales-Analysis-Using-Sql-and-Power-BI/blob/main/Screenshots/sales_overview.png)

### 2️⃣ Product Overview
- Highlights best-selling products.
- Allows filtering by product categories and sales reps.

![Product Overview](https://github.com/muhammed-saheer/Sales-Analysis-Using-Sql-and-Power-BI/blob/main/Screenshots/product_details.png)

### 3️⃣ Customer Overview
- Identifies top customers by revenue.
- Analyzes customer segments and sales trends.

![Customer Overview](https://github.com/muhammed-saheer/Sales-Analysis-Using-Sql-and-Power-BI/blob/main/Screenshots/customer_details.png)


## 📂 Extracted & Cleaned Data  

The following SQL scripts were used to extract and clean the necessary data from the AdventureWorksDW2019 database:

- **DIM_Product**  
  ![DIM_Product](https://github.com/muhammed-saheer/Sales-Analysis-Using-Sql-and-Power-BI/blob/main/Screenshots/product_sql_script.png)

- **DIM_Calendar**  
  ![DIM_Calendar](https://github.com/muhammed-saheer/Sales-Analysis-Using-Sql-and-Power-BI/blob/main/Screenshots/calender_sql_script.png)

- **DIM_Customer**  
  ![DIM_Customer](https://github.com/muhammed-saheer/Sales-Analysis-Using-Sql-and-Power-BI/blob/main/Screenshots/customer_sql_script.png)

- **FACT_InternetSales**  
  ![FACT_InternetSales](https://github.com/muhammed-saheer/Sales-Analysis-Using-Sql-and-Power-BI/blob/main/Screenshots/internetsales_sql_script.png)


## 🏁 Conclusion
- **Sales Performance**: The company’s sales trends indicate a need for targeted improvements in specific product categories.
- **Top Products & Customers**: Certain products and customers contribute significantly to revenue; focusing marketing efforts here could improve growth.
- **Budget Comparison**: Analyzing performance against budget helps in setting realistic targets for the future.
- **Dynamic Filtering**: The Power BI dashboard allows for flexible filtering, making it easier to derive insights.

## 🚀 How to Use
1. **Clone the Repository**
   
sh
   git clone https://github.com/muhammed-saheer/Sales-Analysis-PowerBI.git

2. **Restore Database**
   - Use SQL Server Management Studio (SSMS) to restore AdventureWorksDW2019_DatesUpdated.bak.
3. **Run SQL Scripts**
   - Execute scripts in SQL_Scripts/ to extract required data.
4. **Load Data in Power BI**
   - Open Sales_Report_Dashboard.pbix in Power BI.
   - Refresh queries to update the dashboard.

## 📧 Contact
For any queries, feel free to reach out:
- **LinkedIn**: [Muhammed Saheer K](https://www.linkedin.com/in/muhammed-saheer-k-34a7372a8/)
- **GitHub**: [muhammed-saheer](https://github.com/muhammed-saheer)
- **Email**: saheershan77@gmail.com
     
