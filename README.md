Objective	: Analysis on Sales data through an interactive BI Dashboard.


Data acquisition :	PUBLIC SOURCE SQL SCRIPT EXECUTED IN MYSQLWorkbench, CONNECTING IT TO POWER BI for data transfer to report.

 
Data transformation	: Deleted duplicates from transaction table ,year & month segregation from date in date table, added normalized amount column to transaction table, removed rows with -1/0 sales amount from transaction table, removed rows from market table  having market name ='NY'

 
	
Data modelling 	Schema Design : Designing the logical and physical structure of the database.-->>STAR SCHEMA
	                              Normalization: Organizing data to reduce redundancy and improve integrity.
	                              Defining Relationships: Establishing how different tables relate to each other.


Data visualization : Cards,funnel charts,bar charts,line charts,slicers,pie chart.


Recommendation : Implement machine learning models to study customer behavior & predict future sales trends. 
	              Enable real-time data updates to keep the dashboard current with the latest sales information.
	              Optimize Pricing Strategies
	              Customer Feedback Loop
	              Inventory Optimization
	              Sales Process Automation

 
Sharing :	Exporting Power BI reports to PDF, PowerPoint, and Excel from Power BI service 
	
