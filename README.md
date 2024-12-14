

## About the Project
This project involves performing data analysis and designing a dashboard in Power BI to address critical supply chain issues faced by a growing FMCG manufacturer in Gujarat, India. 

The goal is to identify service delivery problems and provide actionable insights to improve customer satisfaction and retain key customers before expanding to new markets.

---

## Problem Statement
This FMCG manufacturer operates in Surat, Ahmedabad, and Vadodara and plans to expand to other metro and Tier-1 cities in the next two years. However, service delivery issues have resulted in a few key customers not renewing their annual contracts. The suspected issues include:
- Orders not being delivered **on time**.
- Orders not being delivered **in full**.

---

## KPI considered

- Orders not being delivered **on time**.
- Orders not being delivered **in full**
- On Time Delivery **OT%**
- In Full Delivery **IF%**
- On Time In Full **OTIF%**
- Number of Delayed Delivery Days


---

## Data Model
The analysis is based on the following datasets:
1. **dim_customers**: Customer details (name, city, ID).
2. **dim_products**: Product information (name, category, ID).
3. **dim_date**: Date information (daily, monthly, weekly levels).
4. **dim_target_orders**: Target service levels for each customer.
5. **fact_order_line**: Order line details (placement, delivery, quantity, delays).
6. **fact_orders_level**: Aggregate metrics at the order level (OT%, IF%, OTIF%).
  



---

## Dashboard Highlights
The Power BI dashboard includes:
- Key Metrics: **OT%, IF%, OTIF%** compared against targets.
- **Trends**: Monthly trends for key metrics, drillable by weeks and days.
- **Customer Analysis**: Metrics split by customer and city, highlighting customers with the worst performance.
- **Product Analysis**: Delayed product categories and top delayed items.
- **Conditional Formatting**: Highlighting underperforming metrics against targets.
- **Interactive Features**: Drillthrough capabilities and dynamic metric switches.


---

## Key Insights
1. **Overall Performance**: All key metrics (**OT%, IF%, OTIF%**) are consistently below target levels.
2. **Delay Details**:
   - **Coolblue**, **Acclaimed Stores** and **Lotus Mart** have the highest delay in order delivery and fulfillment.
   - **Dairy** products have highest delay in order delivery and fulfilment.
3. **Potential Causes**:
   - Ineffective delivery date estimation.
   - Higher-than-expected order volumes.
   - Production shortfalls impacting IF%.
4. **Lack of Progress**: No noticeable improvements in key metrics over recent months.
5. **Gaps in IF%**: Significant underperformance in IF% for most customers, suggesting possible production or supply chain inefficiencies.

---

## Next Steps
- Investigate the causes of delays (e.g., delivery date estimation, order volumes, production).
- Optimize production planning for high-demand and delayed products.
- Monitor performance regularly and implement targeted interventions for underperforming customers and products.

---

## Conclusion
This dashboard provides with actionable insights into the root causes of delivery issues. By addressing these challenges, the company can improve service levels, retain key customers, and confidently expand into new markets.

---




