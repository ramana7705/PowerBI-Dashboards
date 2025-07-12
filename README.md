📊 Task 1 – Sales Dashboard | Power BI Internship (CODTECH)

👩‍💻 Intern:M Venkata Ramana
🗂️ Internship: CODTECH – Power BI Virtual Internship
📁 File: Task1_SalesDashboard.pbix ✅ Objective To build an interactive Power BI dashboard visualizing sales performance using sample data. 📁 Data Source

File Used: Sample_Sales_Data.xlsx
Fields Included:
Date
Product
Region
Sales Amount
Quantity Sold 🧱 Visual Components | Visual | Purpose | |----------------------------|------------------------------------------| | 📈 Line Chart | Sales trend over time (Date vs Sales) | | 📊 Bar Chart | Top 5 Products by Total Sales | | 🌍 Column/Map Chart | Sales distribution by Region | | 🎛️ Slicers | Date, Product, and Region filters | 📊 Task 2 – dataintegration
Objective: Combine data from at least two different sources (e.g., Excel and CSV) to create a unified Power BI report with meaningful visualizations. 🗂️ Data Sources Used: Sales.xlsx (Excel) – Contains sales transactions Customers.csv (CSV) – Contains customer information 🔗 Relationship Created: Key: CustomerID Type: Many-to-One (Each customer can have multiple transactions) 📈 Visualizations Included:

KPI Card – Total Revenue
Bar Chart – Revenue by Country
Table – Customer Transactions (Customer Name, Product, Quantity, Revenue)
Slicer – Filter by Country 📊 Power BI Task 3 – Real-Time Dashboard (Simulated) This task simulates a real-time Power BI dashboard using a Python script and Excel file. ✅ Objective Create a Power BI dashboard that:
Reads dynamic (changing) data
Visually updates when data is refreshed
Simulates a live real-time feed (e.g., temperature and humidity) 🧪 How It Works
A Python script (update_excel.py) appends a new row every 5 seconds to live_data.xlsx.
Power BI connects to this file.
When you click “Refresh” in Power BI, it updates visuals with the new data. 📁 Project Files | File | Description | |------|-------------| | live_data.xlsx | Excel file receiving new data entries | | update_excel.py | Python script generating data | | run_live_update.bat | Batch file to run the script automatically | | Task3_RealTimeDashboard.pbix | Power BI report file | | README.md | Instructions and project overview | ▶️ How to Use ✅ Install Python Libraries Open terminal or CMD and run: pip install pandas openpyxl numpy 📊 Power BI Task 4: Python Integration 🧠 Task Objective: Use Python scripts inside Power BI to perform advanced data analysis and create custom visualizations. 📌 Dataset: File Used: sarasota_sales.xlsx
This dataset contains sample daily sales data including:
Date
Region
Product
Sales
Profit 🔧 Tools & Technologies Used:
Power BI Desktop
Python 3.x
Python Libraries:
pandas
matplotlib
seaborn ✅ Task Deliverables:
🧮 Data Summarization (Python in Power Query)
Used Run Python Script in Power Query to group sales and profit by Region.
import pandas as pd
summary = dataset.groupby('Region')[['Sales', 'Profit']].sum().reset_index()
summary
