Here are some take-home assignment questions designed to help you learn and apply key data analytics concepts using the synthetic data generated. These questions cover various aspects such as data cleaning, analysis, visualization, predictive modeling, and process optimization.

### **1. Data Cleaning & Preprocessing (Raw Material Procurement Data)**
   - **Question**:  
     Using the `rawmaterial_proc_data` table, perform the following tasks:
     - Check for missing values and describe how you would handle them.
     - Identify and remove any duplicate records if they exist.
     - Convert the `Procurement_Date` column to a proper datetime format.
     - Calculate the total value of each raw material procurement (`Quantity_Ordered * Unit_Price`) and add it as a new column called `Total_Cost`.
     - Filter the data for records where the procurement date is in 2023, and calculate the average procurement quantity for each material type.
     
   **Learning Goals**:
   - Data cleaning
   - Handling missing data
   - Date-time formatting
   - Feature engineering (creating new columns)

---

### **2. Data Analysis & Visualization (Sales Data)**
   - **Question**:  
     Using the `sales_data` table, complete the following tasks:
     - Create a summary table that shows the total sales amount and the total quantity sold for each `Product_ID`.
     - Visualize the sales trend over time (for a period of 6 months). Use a line chart to show the total sales amount by month.
     - Which product has the highest total sales and which has the lowest?
     - Create a bar chart to visualize the total sales for each customer.
   
   **Learning Goals**:
   - Data aggregation
   - Time-series analysis
   - Data visualization with Excel charts (Bar, Line)
   - Customer segmentation based on sales performance

---

### **3. Business Intelligence & KPIs (Manufacturing Data)**
   - **Question**:  
     Using the `manufacturing_data` table, identify key performance indicators (KPIs) that would help monitor the performance of the manufacturing process. Answer the following:
     - Calculate the average number of units produced per day (`Units_Produced / (End_Date - Start_Date)`).
     - Identify the top 5 products that have the highest total units produced.
     - Create a dashboard with the following KPIs:
       - Total units produced per product category
       - Average units produced per day
       - Number of days to complete production per product
  
   **Learning Goals**:
   - Identifying KPIs
   - Calculating production efficiency
   - Dashboard creation (in Excel)

---

### **4. Predictive Modeling (Sales Forecasting)**
   - **Question**:  
     Using the `sales_data` and `manufacturing_data` tables, predict future sales for the next quarter based on historical data. Answer the following:
     - Prepare the data by merging `sales_data` with `manufacturing_data` on `Product_ID`.
     - Choose a predictive model (e.g., linear regression) to predict future sales based on the number of units produced, unit price, and the past sales data.
     - Visualize the predicted sales for the next quarter and compare it with actual sales (if available).
     
   **Learning Goals**:
   - Time-series forecasting
   - Model training and testing
   - Feature selection for predictive modeling
   - Regression analysis in Excel

---

### **5. Process Optimization (Quality Data)**
   - **Question**:  
     Using the `quality_data` table, identify potential areas for improvement in the manufacturing process. Answer the following:
     - Calculate the defect rate for each product (`Defects_Detected / Quantity_Produced`).
     - Which products have the highest defect rates? How would you suggest improving quality control for these products?
     - Create a bar chart showing the number of inspections passed vs. failed for each product.
   
   **Learning Goals**:
   - Quality control analysis
   - Identifying process improvement opportunities
   - Visualization of defect rates and inspection results

---

### **6. Master Data Analysis & Reporting (Master Data)**
   - **Question**:  
     Using the `master_data` table, perform the following:
     - Create a summary report showing the average unit cost for each product category.
     - Find the product with the highest and lowest unit cost.
     - Create a pie chart showing the proportion of products in each category (e.g., Engine Parts, Body Parts, etc.).
   
   **Learning Goals**:
   - Master data analysis
   - Aggregating data by category
   - Visualization of product distribution by category

---

### **7. Advanced Data Analysis: Correlation and Regression (Combining Multiple Tables)**
   - **Question**:  
     Combine the `sales_data`, `manufacturing_data`, and `rawmaterial_proc_data` tables. Answer the following:
     - Use correlation analysis to explore the relationship between procurement quantity, units produced, and sales amount.
     - Conduct a simple linear regression to predict sales amount based on units produced.
     - What insights can you derive from the correlation and regression analysis?
   
   **Learning Goals**:
   - Merging data from different sources
   - Correlation and regression analysis
   - Multivariable analysis using Excel

---

### **8. Data Visualization and Interactive Dashboards (Overall Reporting)**
   - **Question**:  
     Using all the tables (`sales_data`, `manufacturing_data`, `rawmaterial_proc_data`, `quality_data`, and `master_data`), create an interactive dashboard that allows stakeholders to:
     - Filter by product category.
     - View total sales, units produced, and defect rates by product.
     - Compare sales with production efficiency (units produced per day).
   
   **Learning Goals**:
   - Data integration
   - Creating interactive reports in Excel
   - Using slicers and pivot tables for interactive dashboards

---

### **9. Data Insights and Decision Making**
   - **Question**:  
     After analyzing the data from the previous questions, provide a report outlining key insights and actionable recommendations for improving operations. Your report should cover:
     - Product categories with the highest and lowest sales.
     - Manufacturing products with the highest defect rates and suggestions for improvement.
     - Areas where procurement costs can be optimized.
     - Suggestions for improving the sales process based on customer behavior.
   
   **Learning Goals**:
   - Synthesizing data insights
   - Actionable recommendations
   - Report writing for decision-making

---

These questions help cover a wide range of concepts from data preprocessing to predictive modeling and process optimization, using the provided synthetic data. The goal is to apply both theoretical knowledge and practical skills to solve real-world business problems. Let me know if you need further clarification on any of the tasks!