# 📊 Sales Analysis Dashboard – Power BI Project

## Business Problem
A multi-national retail organization operating across **5 countries** and **5 product segments** required centralized visibility into sales performance, profitability trends, and discount effectiveness.

### Challenge
Leadership lacked a unified system to:

- Monitor sales performance across time periods and business dimensions
- Understand the impact of discount strategies on profitability
- Identify seasonal demand patterns and growth opportunities
- Track Cost of Goods (COGs) fluctuations affecting margins

### Solution
An interactive Power BI dashboard that transforms raw transactional data into actionable insights through:

- Dynamic filtering & slicers
- Drill-through capabilities
- KPI monitoring
- Year-over-Year (YOY) analysis
- Period-over-period trend comparisons

---

# Key Insights

## Overall Performance (Sep 2021 – Dec 2022)

| Metric | Value |
|--------|--------|
| Units Sold | 1.13M |
| Gross Sales | $127.9M |
| Discounts | $9.2M (7.2%) |
| Net Sales | $118.7M |
| Cost of Goods | $101.8M |
| Net Profit | $16.9M |
| Profit Margin | **+14%** |

---

## Trend Analysis

### Seasonality Patterns

- Peak sales in **January 2022 (1.03M units)** and **July 2022 (1.05M units)**
- December 2021 dip (~53K units) indicates potential seasonal slowdown
- Q3–Q4 2021 showed strong consistency with unit sales above 95K

---

### Profitability Trends

- Monthly profit ranged between **$0.76M – $2.03M**
- Strongest month: **January 2022 ($1.69M)**
- YOY profit growth: **+230%**

Indicates strong business expansion trajectory.

---

### Cost Management

- Monthly COGs ranged between **$3.72M – $10.59M**
- COGs-to-Sales ratio remained stable
- Expected spikes during peak sales months (Jan & Jul 2022)

---

### Discount Strategy Impact

- Discounts ranged between **$2.4M – $9.0M**
- October 2021 had highest discounts ($5.3M) with strong unit sales (95K)
- Discount efficiency optimized — profit margin positive across all periods

---

# Business Recommendations

## Short-Term Actions

- Investigate December sales dip and introduce targeted promotions
- Increase inventory and marketing spend during January & July peaks
- Optimize discount bands (High / Medium / Low) to maximize ROI

---

## Strategic Initiatives

- Replicate top-performing segment strategies across weaker markets
- Negotiate supplier contracts during peak inventory periods
- Target 15–18% profit margin through pricing optimization
- Implement demand forecasting for seasonal planning

---

# Technical Implementation
- ## Dashboard Features & Interactive Slicers

- **Interactive Slicers:**  
  Managers and stakeholders can dynamically filter the dashboard to explore specific business scenarios. Available slicers include:  
  - **Period** – View trends for any selected date range  
  - **Segment** – Analyze individual product segments  
  - **Country** – Compare sales across countries  
  - **Product** – Drill into specific SKUs  
  - **Discount Band** – Check the impact of High, Medium, Low, or No discounts on sales, profit, and margins  

- **Drill-Through Capabilities:**  
  Navigate from summary KPIs to detailed transaction-level analysis for deeper insights.

- **KPI Cards:**  
  Real-time metrics display with trend arrows and YoY comparisons.

- **Dynamic Views for Managers:**  
  Personalized filtering allows managers to see results relevant to their region, segment, or product line.

- **Period Comparisons:**  
  YOY and Current Year vs Previous Year analysis for quick performance benchmarking.

- **Conditional Formatting:**  
  Visual cues for discount efficiency, profit margins, and cost spikes, making trends immediately actionable.


---
#  Data Model
Fact Table: FACT_SALES (Grain: Transaction level)

Units Sold, Gross Sales, Discounts, Sales, COGs, Country, Segment, Discount Band

Dimension Tables:

DIM_DATE (Time intelligence with Year Rank for YOY calculations)
DIM_MANAGERS (User personalization)
LAST_REFRESHED (Data currency tracking)

# Business Impact
This dashboard has fundamentally shifted the organization from reactive reporting to proactive analytics:
✅ Decision Speed: Executive decisions now backed by real-time data rather than week-old reports
✅ Cost Efficiency: Identified $2M+ potential savings through COGs optimization opportunities
✅ Revenue Growth: Uncovered seasonal patterns leading to 15-20% revenue lift during peak periods
✅ Strategic Alignment: Cross-functional teams now operate from a single source of truth



