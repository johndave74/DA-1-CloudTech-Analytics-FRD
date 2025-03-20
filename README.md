# DA-1-CloudTech-Analytics-FRD
The CloudTech Analytics Dashboard provides an in-depth look into sales, profit, unit performance, and segmentation. The insights derived highlight strong sales and profit growth but also reveal opportunities for market expansion and seasonal sales optimization.

# CloudTech Analytics Dashboard

![CloudTech dashboard](https://github.com/user-attachments/assets/9f22aab5-67af-4158-b8bd-942d6b82dadf)

Welcome to **CloudTech Analytics**! This dashboard provides a comprehensive overview of our sales performance, profitability, unit sales, and market segmentation. It is designed to help stakeholders make data-driven decisions and optimize business strategies.

## 📊 Key Highlights

- **Total Sales:** $118.73M
- **Profit:** $16.89M
- **Total Units Sold:** 1.13M
- **Average Order Value (AOV):** 169.61K
- **Sales Margin:** 349.46%
- **Profit Margin:** 335.58%
- **Unit Sold Margin:** 325.36%
- **AOV Margin:** 12.37%

## 🔍 Insights & Findings

### 1️⃣ Sales Performance
- The total sales stand at **$118.73M**, with a significant increase from the previous year’s **$26.42M**, reflecting strong business growth.
- The **Sales Margin of 349.46%** suggests a remarkable improvement in revenue generation compared to the previous year.

### 2️⃣ Profitability Trends
- The company achieved a **profit of $16.89M**, which is an impressive increase from last year’s **$3.88M**.
- A **profit margin of 335.58%** indicates efficient cost management and increased revenue from high-margin products.

### 3️⃣ Unit Sales Growth
- **1.13M total units sold**, marking an incredible **325.36% growth in unit sales compared to the previous year**.
- The high increase in unit sales suggests strong market demand and successful sales strategies.

### 4️⃣ Product Performance
- **Top-selling products:**
  - **Paseo:** $33M
  - **VTT:** $21M
  - **Velo:** $18M
  - **Amarilla:** $18M
  - **Montana:** $15M
  - **Carretera:** $14M
- Paseo leads in sales, but Amarilla and VTT are also significant contributors to overall revenue.

  **Explanation:** Paseo, VTT, and Velo dominate sales, contributing significantly to overall revenue. Meanwhile, Montana and Carretera underperform, suggesting the need for targeted marketing strategies or product improvements.
- **Recommendation:** Focus marketing efforts on high-performing products while assessing strategies to improve sales of lower-performing ones.

### 5️⃣ Sales by Segment
- The Government sector contributes **$52.50M**, making it the largest revenue-generating segment.
- Small businesses follow with **$42.42M**, showing strong engagement in the SME market.
- Enterprise sales stand at **$19.61M**, presenting an opportunity for further expansion.

- - **Explanation:** The Government sector is the primary revenue driver, while the Enterprise segment lags. This could indicate higher contract values in government procurement compared to private enterprises.
- **Recommendation:** Tailor sales strategies for the enterprise segment to improve profitability by offering customized solutions or competitive pricing.

### 6️⃣ Monthly Sales Trend
- The sales trend is dynamic, peaking in **June ($10M)** and **October ($21M)**.
- Lowest sales occur in **January and February ($7M each)**, indicating potential seasonal fluctuations.
- A steady increase from March to October suggests effective marketing and sales initiatives during these months.

- - **Explanation:** Sales see a significant rise in March, possibly due to seasonal demand, promotions, or product launches. Conversely, sales drop in April, May, and August, signaling potential demand gaps.
- **Recommendation:** Investigate seasonal demand fluctuations and optimize promotional campaigns in low-performing months.

### 7️⃣ Regional Sales Distribution
- **Top-performing countries:**
  - **United States:** $25M
  - **Canada:** $25M
  - **France:** $24M
  - **Germany:** $24M
  - **Mexico:** $20M
- The US and Canada dominate the market, but France and Germany are close competitors.
- Mexico presents an opportunity for deeper market penetration.

- - **Explanation:** North America leads sales, while France and Germany exhibit strong competition. Mexico shows potential growth, requiring further market penetration strategies.
- **Recommendation:** Strengthen supply chain and distribution channels in top-performing countries while exploring expansion strategies for emerging markets.

---

## 📌 Recommendations

✅ **Enhance Market Expansion**
- Leverage the strong demand in **Government and Small Business sectors** by expanding targeted marketing campaigns.
- Explore new market opportunities in the **Enterprise sector**, as its revenue contribution is relatively lower.

✅ **Optimize Seasonal Sales Strategy**
- Address the **January-February sales slump** by introducing promotions, discounts, or loyalty programs during these months.
- Capitalize on high-performing months (**June and October**) with additional marketing efforts to maximize revenue.

✅ **Focus on High-Performing Products**
- Strengthen supply chain and production for **Paseo, VTT, and Velo**, as they generate the highest revenue.
- Identify and address potential gaps in sales for lower-performing products like **Montana and Carretera**.

✅ **Regional Growth Strategy**
- Strengthen marketing efforts in **France and Germany** to close the gap with the US and Canada.
- Increase penetration in **Mexico**, which holds untapped potential.

## 🖩 DAX Measures Used
Below are the **DAX measures** utilized in this dashboard:

```DAX
-- Total Sales
Total Sales = SUM(Sales[Sales Amount])

-- Total Profit
Total Profit = SUM(Sales[Profit])

-- Total Units Sold
Total Units Sold = SUM(Sales[Units Sold])

-- Average Order Value (AOV)
AOV = DIVIDE([Total Sales], [Total Units Sold], 0)

-- Sales PY (Previous Year Sales)
Sales PY = CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Sales[Date]))

-- Profit PY (Previous Year Profit)
Profit PY = CALCULATE([Total Profit], SAMEPERIODLASTYEAR(Sales[Date]))

-- Unit Sold PY (Previous Year Unit Sales)
Unit Sold PY = CALCULATE([Total Units Sold], SAMEPERIODLASTYEAR(Sales[Date]))

-- Sales Margin %
Sales Margin % = DIVIDE([Total Sales] - [Sales PY], [Sales PY], 0) * 100

-- Profit Margin %
Profit Margin % = DIVIDE([Total Profit] - [Profit PY], [Profit PY], 0) * 100

-- Unit Sold Margin %
Unit Sold Margin % = DIVIDE([Total Units Sold] - [Unit Sold PY], [Unit Sold PY], 0) * 100

-- AOV Margin %
AOV Margin % = DIVIDE([AOV] - CALCULATE([AOV], SAMEPERIODLASTYEAR(Sales[Date])), CALCULATE([AOV], SAMEPERIODLASTYEAR(Sales[Date])), 0) * 100
```

## 📈 Conclusion
The **CloudTech Analytics Dashboard** provides an in-depth look into sales, profit, unit performance, and segmentation. The insights derived highlight strong sales and profit growth but also reveal opportunities for market expansion and seasonal sales optimization. By implementing data-driven strategies, we can continue to scale and maximize business performance.

🚀 **Let’s leverage data to drive smarter decisions and greater success!**
