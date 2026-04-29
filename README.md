# Power BI Superstore Dashboard 2015–2018

This is a Power BI dashboard analyzing 9,800 Superstore transactions (2015–2018). Built in Power BI Service across 4 tabs using DAX measures for YoY growth, AOV trends, conditional formatting, and dynamic insight cards. The analysis identifies a 2016 revenue dip, declining order value despite volume growth, Q4 seasonality, and geographic concentration risk.

## Dashboard Walkthrough
[Watch the video walkthrough →](https://youtu.be/meY-78UYSME)

## Dashboard Preview

![Overview](overview.png)
![Revenue Trends](revenue_and_sales_trends.png)
![Segments & Categories](segment_and_category_performance.png)
![Regional Performance](regional_performance.png)

## Files
- `Revenue_and_Performance_Dashboard_2015_-_2018.pbix` — Power BI source file

## Key Findings & Strategic Recommendations

Analysis of 9,800 Superstore transactions (2015–2018) across revenue, order value, seasonality,
and geography surfaced four business risks with strategic implications:

---

### 1. 2016 Revenue Dip — Diagnose Before Scaling
**Finding:** Revenue declined in 2016 despite relatively stable order volume, indicating a
margin or pricing issue rather than a demand problem.

**Recommendation:** Prioritize a pricing and discount audit before investing in customer
acquisition. Revenue-per-order compression often signals over-discounting or unfavorable
product mix shift, both of which scale the wrong way when volume increases.

---

### 2. Declining Average Order Value (AOV) Despite Volume Growth
**Finding:** Order volume grew year-over-year, but AOV trended downward, meaning the business
was acquiring more transactions at a lower value.

**Recommendation:** Rebalance growth strategy toward higher-AOV segments (Corporate and Home
Office outperform Consumer on order value). Introduce upsell/bundle mechanics at checkout and
audit promotional cadences that may be training customers to wait for discounts.

---

### 3. Q4 Seasonality Concentration Risk
**Finding:** Revenue is heavily concentrated in Q4, creating operational and forecasting
fragility for the other three quarters.

**Recommendation:** Develop Q2 and Q3 demand stimulation programs (targeted promotions,
loyalty incentives, or B2B outreach cycles) to smooth the revenue curve. A business dependent
on one seasonal spike is one bad Q4 away from missing annual targets.

---

### 4. Geographic Concentration Risk — West & East Dependency
**Finding:** The West and East regions account for a disproportionate share of revenue, while
the Central and South regions are underpenetrated relative to their market size.

**Recommendation:** Model the revenue opportunity in Central and South using current
performance-per-territory ratios as a baseline. A structured territory expansion or sales
coverage increase in these regions represents the clearest path to incremental growth without
relying on market share gains in already-saturated geographies.

---

### Summary
| Risk | Severity | Recommended Action |
|---|---|---|
| 2016 revenue dip | High | Pricing & discount audit |
| Declining AOV | High | Segment mix rebalancing + upsell strategy |
| Q4 seasonality | Medium | Off-peak demand generation programs |
| Geographic concentration | Medium | Central/South territory expansion modeling |
