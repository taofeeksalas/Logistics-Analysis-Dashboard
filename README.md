# 📦 Supply Chain Performance Dashboard

## 🗂 Table of Contents
1. [Project Background](#project-background)
2. [Executive Summary](#executive-summary)
3. [Insights Deep-Dive](#insights-deep-dive)
4. [Recommendations](#recommendations)
5. [Clarifying Questions, Assumptions, and Caveats](#clarifying-questions-assumptions-and-caveats)
   - [Questions for Stakeholders Prior to Project Advancement](#questions-for-stakeholders-prior-to-project-advancement)
   - [Key Assumptions and Caveats](#key-assumptions-and-caveats)

---

## 📌 Project Background

This dashboard project was developed to  highlights operational challenge faced by a retail distribution company in the US. The business manages thousands of product orders across multiple regions and relies heavily on external shipping companies to fulfil deliveries.


### 🎯 Target Stakeholders:
- **Logistics & Operations Teams** – to track delivery timelines, volume, and bottlenecks.
- **Sales & Marketing** – to identify demand patterns by region and product.
- **Executive Leadership** – to monitor performance KPIs and support strategic decisions.

---

## 🧾 Executive Summary

This project analyses over 5,000 supply chain transactions to uncover operational inefficiencies. While the business maintains a 99.48% delivery rate, over 77% of shipments are late. High-volume products like **Binders** and **Paper** also show the highest undelivered quantities, indicating fulfilment issues. COSCO, the dominant delivery partner (60%), may be a bottleneck. Regional disparities in processing time, especially in the Central region (4.06 days), further suggest the need for targeted operational improvements. This dashboard empowers teams to optimise logistics, prioritise product demand, and enhance delivery performance.

---

## 🔍 Insights Deep-Dive

### Product Fulfilment
- Binders and Paper(office supplies) are top-shipped products but contribute most to undelivered volumes.
- Storage and Accessories also show moderate delivery issues worth monitoring.

### Regional Analysis
- The West accounts for the largest share of orders (32.16%), followed by the East (27.97%).
- Central region has the longest average processing time (4.06 days), indicating fulfilment inefficiency.

### Carrier Performance
- COSCO dominates shipment volume (60.05%), suggesting a need to evaluate service risk and performance.
- Other carriers like APM Maersk and Hapag Lloyd offer opportunity for diversification.

### Delivery Timing
- 4,983 orders delivered, with 93 unshipped and 49 still ongoing.
- 77.9% of shipments are classified as "Late Shipping" based on available timestamp data.

---

## ✅ Recommendations

- **Diversify shipping partners** to reduce reliance on COSCO and improve delivery flexibility.
- **Streamline fulfilment in the Central region** by reviewing warehouse operations and staffing.
- **Prioritise inventory and stock control** for Binders and Paper to reduce backlog.
- **Implement predictive alerts** for delayed SKUs and high-demand regions.

---

## 🧭 Clarifying Questions, Assumptions, and Caveats

### Questions for Stakeholders Prior to Project Advancement
- What are the current SLAs in place with each shipping partner?
- How is late shipping defined internally vs customer perception?
- Are there region-specific challenges (e.g. infrastructure, warehousing) impacting performance?

### Key Assumptions and Caveats
- Delivery timestamps are assumed accurate and aligned with operational cut-offs.
- Data reflects only completed orders up to 2015.
- Region-based processing times assume equal operational capacities across sites.

---

## 💡 Tools & Techniques Used

| Skill Area       | Tools Applied                        |
|------------------|--------------------------------------|
| Data Cleaning    | Excel                           |
| Data Modelling   | DAX, Power BI                        |
| Visual Analytics | Bar, Line, Pie, Donut, Map Visuals   |
| Business Analysis| KPI design, trend interpretation     |

---

