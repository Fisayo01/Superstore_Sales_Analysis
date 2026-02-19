# Superstore Sales Performance and Profitable Analysis (2017-2020)

## 🔍 Problem Statement
The business experienced strong sales growth but faced persistent losses across certain products and customer segments.
Management needed to understand:
1. Why losses were occurring despite high sales volume.
2. Which products, segments, and regions were driving profit and loss.
3. How discounts and product mix were affecting overall profitability.
4. What strategic actions could improve profit without reducing sales.
The objective of this analysis was to identify key drivers of revenue, profit, and loss, and to provide data-driven insights to support better pricing, product, and market strategies.

## 🗂️ Dataset Overview
The analysis was conducted using a retail sales dataset covering the period from 2017 to 2020. Key fields included:
- Order details (Order ID, Date, Quantity, Shipping Mode)
- Customer segments
- Product categories and sub-categories
- Sales and discounts
- Geographic data (Region, State, City)
- Profit metrics
The dataset did not include cost price, which required careful interpretation of profit and loss patterns.
### Raw Dataset: [SuperStore.xlsx](https://github.com/user-attachments/files/25401038/SuperStore.xlsx)

## ⚙️ Analytical Approach
To address the business problem, the following steps were performed:
- Data cleaning and transformation using Excel and SQL
- Creation of calculated measures and KPIs in Power BI (Sales, Order Quantity, Profit, Loss, Margin, YoY growth)
- Segmentation analysis by customer type, product category, and geography
- Identification of loss-making products and discount-driven transactions
- Visualization of insights using an interactive Power BI dashboard

## Data Cleaning Process
### Overview
The Superstore Sales dataset was cleaned and transformed to ensure accuracy, consistency, and usability for sales performance analysis and dashboard development. The cleaning process involved handling missing values, correcting data types, removing duplicates, standardizing text fields, and validating key business metrics.

### Objectives
- Ensure data accuracy and reliability.
- Prepare the dataset for SQL analysis and Power BI visualization.
- Improve data consistency and integrity.
- Enable accurate calculation of KPIs such as Revenue, Profit, and Profit Margin.

### Cleaning Steps Performed
**1. Data Inspection**
Initial data profiling was performed to understand:
- Number of rows and columns.
- Data types of each column.
- Presence of null values.
- Duplicate records.
- Inconsistent text formatting

 **Cleaned Dataset:** [SuperStoreCleaned.xlsx](https://github.com/user-attachments/files/25400827/SuperStoreCleaned.xlsx)

**Tools used:**
- Excel
- PowerBI

**2. Handling Missing Values**
  Findings:
  Dataset contained no critical missing values in key columns such as Sales, Profit, and Product Category.
  *Actions taken:*
  Verify blanks by using filter to check any blank cell.

**3. Removing Duplicate Records**
Duplicates were checked by selecting all the data and clicking on the remove duplicate feature in Excel.
*Action taken:*
Removed duplicate records to prevent double counting.

**4. Standardizing Data Formats**
- Text Standardization
Corrected inconsistent text entries such as:
- Extra spaces (using Trim function)
- Inconsistent capitalization (Proper case function)
- Inconsistent date format: selected the affected column, navigated to Text to Column feature, and then uncheck all delimiters, follow by selecting Date to change the format

**5. Data Type Correction**
Columns data type were properly checked to ensure correct data type
*Action taken:*
Corrected incorrect data types to ensure accurate calculations

**6. Inconsistent text**
Inconsistent text were for using filter.
*Action taken:*
Remove Special Symbols (® and ™) were removed using find an replace feature in Excel.

## 📈 Key Findings & Insights
### 1. Overall Performance
- Total Sales: 2.32M
- Total Orders: 32K
-Total Profit: 273.8K
-Total Loss: 132.9K
Although the business was profitable overall, significant losses were concentrated in specific products and segments.

### Sales Dashboard 📊:
<img width="1039" height="653" alt="Screenshot 2026-02-18 230003" src="https://github.com/user-attachments/assets/14d29e00-001a-410f-a0c0-0ba041b3ad52" />
<img width="1039" height="655" alt="Screenshot 2026-02-18 230406" src="https://github.com/user-attachments/assets/5ee13081-2813-4e81-b574-17087dc75bc8" />

### 2.  Customer Segment Analysis
- The Corporate segment generated the highest sales (876.24K). However, the Corporate segment also recorded the highest losses.
 ✅
 _Insight_:
 Corporate customers drive revenue but at reduced profitability, likely due to aggressive discounting.

### 3. Product Category Performance
- The Technology category generated the highest total profit and order volume.
- The Furniture category recorded the highest profit margin.
- Technology also accounted for the bulk of total orders.
✅ _Insight_:
  Technology drives volume and total profit, while Furniture drives margin efficiency.

### 4. Sub-Category Performance
- Office Machines recorded the highest sales (439.87K).
- Sixteen sub-categories recorded losses, all associated with discounted products.
- Storage and Organisation recorded the highest loss.
✅ _Insight_:
 Excessive discounting is the primary driver of losses across product sub-categories.

### 5. Shipping Mode Analysis
- Regular shipping was the most frequently used mode.
✅ _Insight_:
 Customers prefer cost-effective shipping options, suggesting stable logistics efficiency.

### 6. . Geographic Performance
- Central and East regions performed best in sales and profit.
- New York and California were the top-performing states.
- Franklin Square and Baton Rouge were the highest-performing cities.
✅ _Insight_:
 Revenue and profitability are concentrated in specific geographic markets.

## 💡 Business Implications
- The analysis revealed that:
- High sales volume does not guarantee high profitability.
- Discount strategies significantly impact profit outcomes.
- Certain products and segments consistently underperform.
- Geographic concentration creates both opportunities and risks.

## 🎯 Recommendations
**1. Optimize Discount Strategy**
 Implement discount thresholds and approval controls to prevent profit erosion.
**2. Review Loss-Making Products**
Reassess pricing and positioning of Storage and Organisation and other loss-making sub-categories.
**3. Leverage High-Margin Products**
Increase promotion and bundling of Furniture products to improve overall margins.
**4. Improve Corporate Segment Pricing**
Introduce tiered pricing models to balance competitiveness and profitability.
**5. Enhance Data Quality**
Incorporate cost price and operational cost data for more accurate profitability analysis.

## 🚀 Project Impact
 This analysis provided a clear understanding of the drivers of sales and profit, enabling stakeholders to:
- Identify loss-making products and segments.
- Improve pricing and discount decisions
- Align product strategy with profitability goals.
- Focus growth efforts on high-performing regions.
- The Power BI dashboard served as a decision-support tool for monitoring performance and guiding strategic actions.
