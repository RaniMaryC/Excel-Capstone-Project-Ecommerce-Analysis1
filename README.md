# Excel Capstone Project - E-commerce Sales Analysis

Analysis of 2,000 e-commerce orders to find which Category, Region, and Loyalty Tier drive the most sales.

File: `Excel Capstone Project - E-commerce Analysis.xlsx`

**Total Sales:** ₹21,74,024 | **Total Orders:** 2,000 | **Average Order Value:** ₹1,087.01

## Tools Used
Microsoft Excel, Pivot Tables, VLOOKUP, Descriptive Statistics (Analysis ToolPak), Charts - Bar, Column, Doughnut

## Data Cleaning Done
1. Joined 3 master tables using VLOOKUP - Category, Region, Loyalty
2. Created Total_Amount = Quantity * Unit_Price
3. Found Missing Values:
   - ₹46,059 (2.1%) sales as Unknown Category
   - ₹17,513 (0.8%) sales as Unknown Tier
4. Checked duplicates, blank rows, negative values - none found

## Key Insights
**Category:** Sports is top at ₹5,42,003 (24.9%), Electronics ₹5,05,875 (23.3%). Together 48% of sales. Beauty lowest at ₹3,01,118 (13.9%).

**Region:** North ₹6,43,565 (29.6%), South ₹6,34,885 (29.2%) and East ₹6,24,868 (28.7%) are almost equal. West very low at ₹2,70,706 (12.5%) - needs investigation.

**Loyalty Tier:** Platinum highest at ₹6,55,317 (30.1%). Bronze ₹5,23,700 (24.1%), Gold ₹5,18,192 (23.8%), Silver lowest at ₹4,59,302 (21.1%).

## Descriptive Statistics - Total_Amount
- Mean: ₹1,087.01 | Median: ₹868.50 | Mode: ₹571
- Standard Deviation: ₹818.88 | Min: ₹18 | Max: ₹3,908 | Skewness: 0.88
- Interpretation: Mean > Median, so distribution is right-skewed. Most orders are small, few high-value orders pull average up.

## Charts
1. Bar Chart - Sales by Category
2. Doughnut Chart - Sales by Region (%)
3. Column Chart - Sales by Loyalty Tier
All charts are in the `Dashboard` sheet.

## Recommendations
1. Focus marketing on Sports & Electronics - top 2 categories.
2. Retain Platinum customers - they give 30% revenue.
3. Investigate West Region - low sales may be logistics or pricing.
4. Fix Master Data - add missing Category_ID and Tier_ID.
5. Promote Beauty category with bundles.

## How to Use This File
1. Open Capstone Excel file
2. Start from `Summary` sheet for insights
3. Go to `Dashboard` for charts
4. Check `Final Sheet` for cleaned data
