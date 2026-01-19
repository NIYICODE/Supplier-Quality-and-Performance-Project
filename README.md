# Supplier-Quality-and-Performance-Project

In this project, I unified supplier quality data, built performance metrics, and benchmarked vendors to surface high-risk suppliers and operational inefficiencies that shaped procurement decisions.

## **Project Overview**
Manufacturing operations rely on external suppliers for critical materials, yet the organization lacked an evidence-based method to evaluate supplier quality or understand the operational consequences of defects across plants. This project transforms fragmented supplier quality data into decision-grade intelligence to guide procurement strategy and reduce downtime-related losses.

## **Purpose**
**Primary Goal:** Benchmark supplier performance using quantitative quality metrics and comparative analysis to support more objective vendor decisions and operational improvements.

**Secondary Goal:** Surface hidden inefficiencies by examining the interaction between vendors, materials, and plants — an operational blind spot prior to this analysis.

## **Technical Stack**
- **Power BI** — data modeling, interactive analytics, DAX metrics
- **Power Query** — ETL, cleaning, formatting, standardization
- **DAX** — metric engineering (defect severity, downtime impact, cross-plant variance)
- **Excel / CSV** — upstream operational data sources

## **Data Characteristics**
The consolidated dataset includes:
- Vendor
- Plant
- Material
- Defect quantity
- Downtime minutes (severity proxy)
- Time attributes (where available)

The dataset originated from multiple plants, requiring standardization and transformation before comparative benchmarking was feasible.

## **5. Analytical Narrative & Key Questions**

### **Business Problem**
Supplier quality issues cause operational downtime, slow production cycles, and increase cost of failure. However, without standardized metrics, performance reviews were anecdotal — high-risk suppliers blended into averages, and procurement lacked defensible insights for negotiation or exit decisions.

### **Analytical Questions**
The analysis sought to answer:
1. Which vendors cause the most defects?
2. Which vendors are most responsible for downtime?
3. Where do vendor–material combinations systematically underperform?
4. Does performance shift across plants for the same vendor?
5. Where does operational risk concentrate — and why?

These map directly to procurement risk, operational reliability, and cost containment.

## **Analytical Approach**

### **Data Structuring & Metric Engineering**
- **Defect Metrics:** to quantify failure frequency
- **Downtime Metrics:** to quantify failure severity
- **Performance Rankings:** to benchmark suppliers
- **Cross-Plant Variance:** to detect instability and inconsistency
- **Vendor–Material Interactions:** to expose systemic coupling failures

This reframed supplier evaluation as a **quantitative performance problem**, not a compliance exercise.



## **Visual Storytelling & Analytical Findings**
### **A. Identifying High-Risk Suppliers**

The first layer surfaced vendors with disproportionate downtime relative to defect count — an early signal of systemic quality failures.

![Vendor Performance](["C:/Users/DELL/Pictures/Screenshots/VendorAnalysis.png"](https://github.com/NIYICODE/Supplier-Quality-and-Performance-Project/blob/39ef8d64f0132482844caef5d334ab46b3343d24/pictures/VendorAnalysis.png))

