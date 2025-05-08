# SUPPLY-CHAIN-MANAGEMENT-DASHBOARD

Dashboard Link :
https://public.tableau.com/app/profile/jyoti.prakash.das7554/viz/Supplychainmanagement_tableau_dashboard/Dashboard_SCM
------------------------------------------------------------------------------------------------------------------------
Project Summary
Objective: 
Build a dashboard to monitor and optimize supply chain operations.
Scope: 
Covers inventory, orders, suppliers, transport, and cost.
Tools Used:
Excel (Data Cleaning ,Formatting)
Tableau (Visualization)  
-------------------------------------------------------------------------------------------------------------------------
Dataset Overview
Industry: 
Fashion & Beauty Co.
Products:
Cosmetics , Haircare and Skincare.
Key Fields: 
SKU, Product Type, Price, Lead Time, Cost, Defect Rate, etc.
Original Format:
Single Excel sheet with 24 columns.
-------------------------------------------------------------------------------------------------------------------------
Data Preparation
Split single dataset into 5 Topic-based tables: 
Inventory, Orders, Suppliers, Transport, Costs.
Generated missing fields: 
Dates, IDs etc.
-------------------------------------------------------------------------------------------------------------------------
Inventory Dashboard
Bar Chart: Inventory Level by Product and Warehouse.
Line Chart: Inventory Trend Over Time.
KPI: Days of Inventory Remaining calculated using Sales & Inventory.
    Sum([inventorylevel])/avg([Daily sales])
-------------------------------------------------------------------------------------------------------------------------
Order Fulfillment Dashboard
Line Chart: Order Fulfillment Over Time.
Bar Chart: On-Time Delivery by Product.
KPI: On-Time Delivery Rate = 90%.
-------------------------------------------------------------------------------------------------------------------------
Supplier Performance Dashboard
Bar Chart: Average Delivery Time by Supplier.
Line Chart: Defect Rate Trend.
KPI: Avg. Delivery Time = 17 Hours, Avg. Defect Rate = 1.26%.
-------------------------------------------------------------------------------------------------------------------------
Transportation Efficiency Dashboard
Scatter Plot: Transit Time by Carrier.
Line Chart: Delivery Status Over Time.
KPI: 90% deliveries on time, 
          Avg. Transit Time = 16 Hours.
-------------------------------------------------------------------------------------------------------------------------
Supply Chain Costs Dashboard
Pie Chart: Cost Type Distribution.
Line Chart: Monthly Cost Trend.
KPI: Total Cost = $52,925
-------------------------------------------------------------------------------------------------------------------------
Conclusion
The dashboard centralizes key performance metrics of the supply chain.
Supports real-time decision-making and cost optimization.
         
