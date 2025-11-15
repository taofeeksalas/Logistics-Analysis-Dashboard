#  Logistics Performance Dashboard

## 🗂 Table of Contents
1. [Project Background](#project-background)
2. [Executive Summary](#executive-summary)
3. [Insights Deep-Dive](#insights-deep-dive)
4. [Recommendations](#recommendations)
5. [Clarifying Questions, Assumptions, and Caveats](#clarifying-questions-assumptions-and-caveats)
   - [Questions for Stakeholders Prior to Project Advancement](#questions-for-stakeholders-prior-to-project-advancement)
   - [Key Assumptions and Caveats](#key-assumptions-and-caveats)

---

##  Project Background

This dashboard project was developed to  highlights operational challenge faced by a retail distribution company in the US. The business manages thousands of product orders across multiple regions and relies heavily on external shipping companies to fulfil deliveries.


###  Target Stakeholders:
- **Logistics & Operations Teams** – to track delivery timelines, volume, and bottlenecks.
- **Sales & Marketing** – to identify demand patterns by region and product.
- **Executive Leadership** – to monitor performance KPIs and support strategic decisions.

---

## 🧾 Executive Summary

This project analyses over 5,000 supply chain transactions to uncover operational patterns and fulfilment performance across regions and product categories. The business maintains a strong 99.48% delivery rate, with Binders and Paper showing the highest undelivered volumes, highlighting areas for inventory and logistics attention. The Central region has the longest average processing time at 4.03 days, suggesting operational improvement opportunities. Shipping method analysis shows a clear customer preference for Standard and Economy shipping, which together make up more than 77% of all deliveries. This dashboard provides stakeholders with visibility into fulfilment trends, shipping method adoption, and delivery statuses to support operational decision-making.

---
##  Enterprise Relational Diagram
![ERD](https://github.com/taofeeksalas/supply-chain-dashboard/blob/main/powerbi/img/ERD.PNG?raw=true)

##  Insights Deep-Dive

### Product Fulfilment
- Binders and Paper(office supplies) are top-shipped products but contribute most to undelivered volumes.
- Storage and Accessories also show moderate delivery issues worth monitoring.

### Regional Analysis
- The West accounts for the largest share of orders (32.16%), followed by the East (27.97%).
- Central region has the longest average processing time (4.06 days), indicating fulfilment inefficiency.

##  Exec Overveiw
![ERD](https://github.com/taofeeksalas/supply-chain-dashboard/blob/main/visuals/Executive%20Overview.PNG)

### Carrier Performance
- COSCO dominates shipment volume (60.05%), suggesting a need to evaluate service risk and performance.
- Other carriers like APM Maersk and Hapag Lloyd offer opportunity for diversification.

### Delivery Timing
- 4,983 orders have been successfully delivered.
- 93 remain unshipped, and 49 are currently in transit (Delivery Ongoing)
- The majority of shipments follow standard or economy fulfilment timelines; there is no classification for “Late Shipping” in the current dataset

---
##  Logistics Details
![ERD](https://github.com/taofeeksalas/supply-chain-dashboard/blob/main/visuals/Logistics%20Detail.PNG)

##  Recommendations

### 1. **Diversify Shipping Partners**
Reduce operational dependency on **COSCO**, which currently dominates shipment volume. This reliance introduces risk in the event of service disruptions or performance inconsistencies.  
Evaluate performance benchmarks across alternative partners and gradually redistribute volume to create resilience and improve overall delivery flexibility.

### 2. **Streamline Fulfilment in the Central Region**
The **Central** region shows the highest average processing time (**4.03 days**). Investigate potential root causes such as warehouse layout, staffing levels, and order prioritisation.  
Optimising these areas could significantly reduce processing delays and support more consistent delivery performance across all regions.

### 3. **Improve Inventory Control for Binders and Paper**
**Binders** and **Paper** account for the highest undelivered volumes. Implement tighter inventory management practices, such as real-time stock tracking and reorder point automation.  
Coordination between demand forecasting and procurement can help reduce stockouts and fulfilment gaps.


---

##  Clarifying Questions, Assumptions, and Caveats

### Questions for Stakeholders Prior to Project Advancement
- What are the current SLAs in place with each shipping partner?
- How are undelivered volumes currently prioritised or followed up?
- Are there region-specific challenges (e.g. infrastructure, warehousing) impacting performance?

### Key Assumptions and Caveats
- Delivery timestamps are assumed accurate and aligned with operational cut-offs.
- Analysis focuses on orders fulfilled between 2018 and 2021 as per available data.
- Region-based processing times assume equal operational capacities across sites.

---

##  Tools & Techniques Used

| Skill Area       | Tools Applied                        |
|------------------|--------------------------------------|
| Data Cleaning    | Excel,Power BI                       |
| Data Modelling   | DBdiagram , Power BI                 |
| Visual Analytics | Bar, Line, Pie, Donut, Map Visuals   |

---

