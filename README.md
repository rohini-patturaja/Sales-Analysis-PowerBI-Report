# From Spreadsheet Chaos to $2M in Hidden Savings  
## A Retail Analytics Transformation

---

## The Problem Nobody Was Talking About

Picture this: Five country managers sitting in a quarterly review meeting, each presenting different sales numbers for the same product.

- One claimed profitability was up 15%.
- Another showed a 3% decline.
- The CFO couldn't figure out who was right.

Everyone was pulling data from different sources, using different formulas, and defining "profit" differently.

This wasn't just a data problem—it was a decision-making crisis.

The organization was generating **$127.9 million in sales** across 5 countries and 5 product segments, but leadership was flying blind.

They'd ask simple questions like:
- "Are our discounts actually working?"
- "Why did December sales tank?"

And get five different answers depending on who they asked.

I was brought in to solve what seemed like a straightforward dashboard request.  
What I discovered was far more interesting.

---

## The Investigation

I started where every good analysis begins: with curiosity and a lot of questions.

When I mapped out 15 months of transactions (September 2021 to December 2022), a pattern emerged.

### Key Observations:

- **January 2022:** 1.03M units sold  
- **July 2022:** 1.05M units sold  
- **December 2021:** 53,000 units sold  

That’s a **95% drop from peak to trough**.

Something was happening in December that nobody had investigated.

---

### The Discount Mystery

- October 2021 showed **$5.3M in discounts** (highest all year)
- Sold only **95,000 units**
- Other months with half the discounts sold more

Were we just burning money on unnecessary price cuts?

The answer wasn’t simple—and that’s what made it interesting.

---

## Building the Solution: More Than Just a Dashboard

I didn’t just build charts. I built a system that answered questions leaders didn’t know they should be asking.

---

## The Technical Challenge

The raw data included:

- 1.13M transaction-level records  
- Five countries with different fiscal calendars  
- Three inconsistent discount tiers  
- Monthly COGS fluctuating between $3.72M and $10.59M  

---

## Data Model Architecture

I implemented a **star schema model**:

- `FACT_SALES` (transaction grain)
- `DIM_DATE` (custom year ranking for YOY)
- `DIM_MANAGERS` (role-based filtering)
- `LAST_REFRESHED` timestamp for transparency

This became the **single source of truth**.

---

## Interactive Features ("Aha!" Moments)

Managers could:

- Filter by country to explore profitability trends
- Slice by discount band to evaluate margin impact
- Drill from KPI → Segment → Product → Transaction

The dashboard didn’t just show data.  
It taught analytical thinking.

---

# Strategic Discoveries

---

## Finding #1: The December Dip

December had the **lowest promotional spend** of any month.

Marketing assumed people don’t buy in December.

Competitors were running aggressive campaigns.

### Action Taken:
Increased December promotional budget by 40% in 2023.

---

## Finding #2: Segment-Based Discount Impact

High Discounts:

- Government Segment → 18% margin (good)
- Small Business Segment → 9% margin (poor)

The issue wasn’t discount size.  
It was discount placement.

### Action Taken:
Segment-specific discount policies  
Projected savings: **$2M+ annually**

---

## Finding #3: The July Sales Spike

July consistently hit peak sales (1.05M units).

Root cause:
Government fiscal-year budget cycles.

### Action Taken:
- Dedicated June–July government sales push  
- Targeted inventory planning  

---

# Quantified Business Impact

| Metric | Result |
|--------|--------|
| YOY Profit Growth | 230% |
| Identified Savings | $2M+ |
| Revenue Lift (Peak Periods) | 15–20% |
| Analyst Time Saved | 40+ hours/week |

---

# Cultural Transformation

### Before:
- 3-hour quarterly review arguments
- Weeks to generate custom reports
- Gut-feel decision making

### After:
- 90-minute action-focused reviews
- Real-time self-service insights
- Data-backed strategic planning

---


## Conditional Formatting Rules

- Profit margins < 12% → Red alert
- Discount efficiency < 1.5x → Yellow warning
- COGS spike >15% MoM → Investigation flag

---

## Drill-Through Flow

Summary KPI  
→ Segment Detail  
→ Product-Level Transactions  

Three-click deep dive from board-level to SKU-level.

---

# Lessons Learned

## What Worked
- Starting with business questions
- Building interactivity for exploration
- Creating a trusted single source of truth

## Future Improvements
- ARIMA forecasting for seasonality
- Real-time data refresh
- Mobile-optimized dashboards

---

# The Bottom Line

This wasn’t just a Power BI project.

It transformed:
- Spreadsheet chaos → Strategic clarity
- Reactive reporting → Proactive insights
- “I think” → “I know”

And it all started with one question:

> Why is December so different from January?

Sometimes the best analytics projects begin not with data, but with curiosity.
