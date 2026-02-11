# ​Online Sales & Profitability Analysis (Advanced Excel)
## Business Objectives
​The primary goal of this analysis is to leverage data-driven insights to solve three critical business challenges:

​**Identify Underperforming Regions:** Pinpoint which geographical markets are contributing most to the net loss despite high sales volume.

**​Identify Underperforming Products:** Isolate specific items in the catalog that are "loss leaders" and eroding profit margins.

**​Uncover Sales Trends Over Time:** Analyze the temporal patterns of sales and profit to determine if performance is improving or declining across quarters and months.

## Technical Workflow & Features
### ​1. Data Cleaning & Transformation
**Data Standardization:** Processed raw transactional data to ensure consistent date formats and currency (GBP) for over **49,000 records**.

​**Integrity Checks:** Validated the "Profit" and "Sales" columns to accurately report a total revenue of **£60.1M** against a net loss of **-£704,589.85**.

​**Data Structuring:** Organized product descriptions and country codes for seamless mapping into Pivot Tables and Charts.

### ​2. Advanced Metrics & "Live" Measures
​I developed custom measures and calculated fields to ensure the dashboard remains dynamic:

​**AOV Calculation:** Created a measure for **Average Value Order (£1,240.21)** by dividing Total Revenue by Total Shipments.

**​Profitability Tracking:** Implemented logic to track the divergence between revenue and profit across different timeframes.

**​KPI Integration:** Built live-updating cards for **Revenue**, **Total Profit**, and **Shipment Records** that respond instantly to user input.

### ​3. Interactive User Interface
​**Dynamic Slicers:** Integrated 

**Quarterly (Q1–Q4)** and

**Monthly (Jan–Dec)** slicers to allow stakeholders to drill down into specific timeframes.

**​Connected Visuals:** All charts, including the Sales vs. Profit line graphs and Geographical bar charts—are interconnected to provide a "live" feel as data is filtered.

## Detailed Analysis Findings
### **​1. Sales & Profit Trends Over Time**
**​Stagnation & Decline:** The "Sales vs Profit Overtime" chart reveals that while sales remained steady for most of the year, there was a **sharp decline toward the final period**.

**​Static Losses:** Most concerning is that the profit line remains consistently below the zero axis, indicating the business never reached a break-even point regardless of sales volume.
### **​2. Underperforming Regions**
​**Deepest Losses:** **France** and **Belgium** are the primary underperformers, showing the most significant negative profit margins.

**​Global Deficit:** Even the "Top Performing" region (**U.S.A**) is currently operating at a loss, suggesting a systemic issue with international shipping costs or regional pricing.

### **​3. Underperforming Products**
**​Primary Loss Drivers:** **Blue Pens**, **White Mugs**, and **Office Chairs** were identified as the most unprofitable items.

**​Category Analysis:** The data shows that even high-ticket items are failing to generate positive returns, highlighting a need to renegotiate supplier Cost Of Goods Sold or adjust retail pricing.

## Strategic Recommendations

1. **​Trend Correction:** Investigate the cause of the late-year sales drop to prevent a total collapse in revenue.
2. **​Market Optimization:** Conduct a deep dive into the **France** and **Belgium** markets to identify if taxes, tariffs, or high logistics costs are the cause of the extreme underperformance.
3. **​Product Audit:** Re-evaluate the viability of the "Blue Pen" and "Office Chair" categories, as their current sales volume is actively damaging the company's financial health
   
![Dashboard](Online_sales_dashboard.jpg)
