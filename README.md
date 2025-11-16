# AERO_Sales_Analysis_Dashboard
This Excel-based analysis explores Aero’s 2014 sales performance, uncovering revenue patterns, regional strengths, and top-performing sales representatives. Using PivotTables, charts, and advanced formulas, the project transforms raw transactional data into meaningful business insights that reveal hidden growth opportunities.



<img width="1297" height="532" alt="AERO SALES DASHBOARD" src="https://github.com/user-attachments/assets/54a28b96-6e19-436b-8224-8ed8ddf74008" />



1. Introduction 
This project presents a detailed analysis of Aero’s 2019 sales performance using Microsoft 
Excel. The goal is to uncover key revenue drivers, customer behavior trends, and regional 
strengths while identifying actionable strategies for future growth. 
By translating transactional records into a visual dashboard, the analysis offers insight into 
Aero’s sales distribution, product performance, and payment dynamics across multiple 
dimensions such as region, customer type, and salesperson efficiency. 
2. Story of Data 
The dataset represents Aero’s complete 2019 commercial records, including regional sales, 
customer segmentation, payment methods, and product categories. Each transaction provides 
measurable indicators of Aero’s operational success and market reach. 
Data Source: 
Downloaded from Kaggle.com 
Data Structure: 
Each row represents an individual sales transaction, with key columns capturing region, sales 
representative, payment method, customer type, product category, and transaction amount (in 
GBP). 
| Region | Customer Type | Product Category | Payment Method | Salesperson | Sales Amount | 
Important Features and Significance: 
• Region: Helps assess geographic market strengths and weaknesses. 
• Customer Type: Differentiates between new and returning buyers. 
• Payment Method: Reveals purchasing behavior preferences. 
• Product Category: Identifies profitable lines and lagging products. 
• Salesperson: Measures team and individual performance. 
• Sales Amount: Primary indicator for revenue evaluation. 
Data Limitations: 
The dataset covers only one fiscal year, limiting long-term trend analysis. Customer 
demographic details are also not included. 
3. Data Splitting and Preprocessing 
Data Cleaning: 
• Duplicates were removed using Excel’s Remove Duplicates function. 
• Blank fields in “Payment Method” were corrected via cross-verification. 
• Outlier values (unusually high or low) were flagged using Conditional Formatting. 
Handling Missing Values: 
Missing product entries were replaced with “Uncategorized,” while unrecorded customer types 
were treated as “New” for standardization. 
Data Transformations: 
• Added Region Total and Product Category Total using the SUMIFS function. 
• Created segmentation fields (e.g., “Top 5 Sales Reps”) using rank-based formulas. 
Industry Context: 
The data reflects the Fast-Moving Consumer Goods (FMCG) market, where understanding 
product mix, customer loyalty, and channel efficiency directly drives profitability. 
Stakeholders: 
• Aero’s Sales & Marketing Division 
• Regional Managers 
• Corporate Strategy Teams 
Value to the Industry: 
Demonstrates how structured Excel analytics can uncover both immediate and strategic sales 
optimization opportunities for consumer brands. 
4. Pre-Analysis 
Early data review showed clear indicators of strong brand loyalty, with returning customers 
contributing almost half of total revenue. 
The East and North regions appeared most active, accounting for the largest market shares. 
Initial inspection of sales reps suggested two individuals consistently outperforming others 
hinting at the importance of individual sales skill and client management. 
5. In-Analysis 
Using Excel’s PivotTables and dashboard visualization tools, the data was segmented into key 
focus areas: 
a. Regional Distribution 
Sales were nearly evenly split among regions, with the North (£1.37M) slightly outperforming 
other areas. 
This balanced distribution suggests Aero’s broad market coverage but hints that no region 
achieved exceptional dominance. 
b. Customer Type 
• Returning customers: £2.51M 
• New customers: £2.50M 
This near-parity underscores Aero’s strong customer retention rate and consistent 
acquisition efforts. 
c. Payment Behavior 
• Credit Cards led with £1.76M, followed closely by Bank Transfers (£1.72M). 
• Cash sales (£1.54M) trailed, suggesting that Aero’s clientele leans toward digital or 
bank-based transactions a sign of modern consumer preference. 
d. Top Sales Representatives 
• David (£1.14M) and Bob (£1.08M) were standout performers. 
• The gap between top and lower performers (Charlie at £0.86M) indicates potential 
differences in territory size, experience, or lead quality. 
e. Product Category Performance 
• Clothing dominated with £1.31M, followed by Furniture (£1.26M) and Electronics 
(£1.24M). 
• The Food category (£1.20M) showed stable but modest results. 
This suggests Aero’s strength lies in lifestyle and durable goods, with opportunities to 
grow its food portfolio. 
f. Sales Trend (Seasonality) 
Sales peaked in January (£495K) and dipped significantly in February (£369K). Minor 
fluctuations persisted across the year, with small rebounds in August (£443K) and October 
(£460K). 
These waves likely align with consumer behavior high post-holiday demand, a mid-year lull, and 
Q4 retail surges. 
6. Post-Analysis and Insights 
1. Revenue Concentration: Nearly 40% of sales were driven by top two reps, creating 
dependence risk but also identifying mentoring opportunities. 
2. Regional Stability: Balanced regional distribution provides a safety net against local 
downturns. 
3. Loyal Customer Base: Returning buyers match new ones, confirming brand trust. 
4. Product Expansion Opportunity: Clothing and furniture can anchor premium 
campaigns; food category deserves innovation investment. 
5. Seasonality Planning: Marketing budgets could target February and May for revival 
campaigns. 
7. Data Visualizations & Dashboard 
The Excel dashboard combined PivotCharts, Slicers, and Dynamic Ranges to create an 
interactive and visually intuitive experience. 
Included Visuals: 
• Pie Chart: Sales by Region 
• Donut Chart: Sales by Customer Type 
• Column Chart: Payment Methods 
• Bar Chart: Top Performing Sales Reps 
• Horizontal Bar Chart: Product Categories 
• Line Chart: Monthly Sales Trend 
Dashboard Features: 
• Filters for Region, Customer Type, and Salesperson 
• Real-time interaction via Slicers 
• Clean, consistent color palette reflecting Aero’s brand identity 
8. Recommendations and Observations 
Actionable Insights: 
• Develop a mentorship program pairing top sellers (David, Bob) with newer reps to 
replicate success. 
• Expand regional promotions in West and South to capture untapped potential. 
• Introduce loyalty rewards for returning customers to deepen retention. 
• Increase marketing push during low months (Feb–May) using seasonal offers. 
• Explore digital payment partnerships to further leverage card transactions. 
Strategic Optimizations: 
• Leverage product data to refine inventory planning and reduce underperforming SKUs. 
• Track regional campaigns quarterly to identify micro-trends. 
Unexpected Findings: 
Despite similar revenue shares between regions, individual rep output varied greatly, suggesting 
sales training and client management, not geography, drive performance. 
9. Conclusion 
This Excel-based project demonstrates how Aero’s 2019 sales data can be transformed into a 
clear business intelligence tool. 
Key takeaways include strong returning customer performance, balanced regional contribution, 
and identifiable high-performing staff.
