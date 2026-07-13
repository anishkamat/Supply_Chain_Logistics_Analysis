# 📊 Supply Chain Analytics

An end-to-end business intelligence platform that translates **100,000+ annual transactional records** into actionable executive insights for a global e-commerce enterprise. This project is structured as a professional case study demonstrating advanced data modeling, complex DAX engineering, and executive-level dashboard architecture.

---

## 📈 Strategic Business Impact
Global supply chains frequently suffer from fragmented visibility, leading to unoptimized carrier spend, unexpected stock-outs, and unmitigated shipping delays. 

This analytics platform bridges that gap for executive leadership (COO, Logistics Directors, and Warehouse Managers) by answering critical operational questions:
*   **Financial & Carrier Strategy:** Where are shipping costs eroding net margins, and which logistics routes need renegotiation?
*   **SLA Accountability:** What are the programmatic root causes behind delivery bottlenecks, and which carriers fail to meet compliance targets?
*   **Risk & Reliability:** Which regional warehouses are facing critical inventory depletion, and which suppliers present high damage liabilities?

---

## 📐 Analytics Schema & Data Engineering
*   Designed and deployed a high-performance **Star Schema** optimization, mapping a centralized transactional fact table (`Fact_Orders`) across 5 discrete dimension tables (`Dim_Product`, `Dim_Customer`, `Dim_Supplier`, `Dim_Warehouse`, and `Dim_Partner`).
*   Configured efficient data transformation steps within Power Query to handle messy real-world anomalies across 45 unique operational attributes.

---

## 🧮 Corporate KPI Architecture (DAX Engine)
I engineered the central analytical measures using advanced DAX to enforce corporate benchmarking standards and track supply chain efficiency:

*   **On-Time Delivery (OTD %):** Evaluates carrier performance against an enterprise 85% SLA benchmark.
    
    $$\text{OTD \%} = \left( \frac{\text{Total On-Time Orders}}{\text{Total Orders}} \right) \times 100$$

*   **Net Profit:** Dynamically calculates true bottom-line earnings by subtracting item manufacturing and shipping costs from gross revenue.
    
    $$\text{Net Profit} = \text{Revenue} - (\text{Item Cost} + \text{Shipping Cost})$$

*   **Net Profit Margin %:** Tracks profitability efficiency relative to total gross item revenue.
    
    $$\text{Net Profit Margin \%} = \left( \frac{\text{Total Net Profit}}{\text{Total Item Revenue}} \right) \times 100$$

*   **Product Damage Rate %:** Isolates supply chain quality issues and carrier transit handling risks.
    
    $$\text{Product Damage Rate \%} = \left( \frac{\text{Count of Damaged Items}}{\text{Total Orders Received}} \right) \times 100$$

*   **Order Return Rate %:** Measures reverse logistics volume to flag product dissatisfaction or systemic ordering friction.
    
    $$\text{Order Return Rate \%} = \left( \frac{\text{Count of Returned Items}}{\text{Total Orders Received}} \right) \times 100$$

---

## 🗺️ Dashboard Architecture & Visual Flow

<img width="886" height="500" alt="dashboard homepage" src="https://github.com/user-attachments/assets/d4fb669d-50d6-4105-931b-988c513c80a8" />


---

## 🔍 Data Insights & Recommendations
*   **Fulfillment Bottlenecks:** Root-cause analysis revealed that *Customs Clearance Delays* represented the single largest contributor to missed delivery targets. *Strategic Recommendation: Implement regional buffer windows or update international brokerage documentation workflows.*
*   **Inventory Exposure:** Identified that approximately 15% of active inventory lines routinely dip below safety thresholds. *Strategic Recommendation: Deploy dynamic reorder points tied to moving historical regional averages.*
*   **Revenue Concentration:** Confirmed *Electronics* as the primary revenue and profit driver, with the *East Region* anchoring the largest market share.

---
