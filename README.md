# 📊 Retail Sales Audit: Revenue Drivers, Customer Economics & Inventory Risk

This repository presents a structured 7-day audit of an e-commerce dataset aimed at identifying revenue drivers, improving customer economics, and reducing inventory risk through data-driven decision-making.

**Result:** The audit uncovered multiple profit levers with the potential to increase annual profitability by **8–12%** through retention optimization and assortment rationalization.

---

## 🛠 Tech Stack & Analytical Scope

**Language:** Python 3.x
**Core Libraries:** Pandas, Matplotlib, Seaborn

**Methods Applied:**

* Advanced Data Cleaning & Validation
* Unit Economics (AOV)
* Customer Segmentation (VIP / Retention)
* Pareto Analysis (80/20)
* Outlier Detection
* Seasonality Modeling

---

## 🧹 Data Integrity Audit

Prior to analysis, a deep validation process removed **11,805 rows** of transactional noise, including returns, missing customer IDs, and zero-price entries.

**Critical Adjustment:**
`DOTCOM POSTAGE` was excluded from product metrics to prevent logistics revenue from distorting true retail demand.

👉 This step ensured that all downstream insights reflect actual purchasing behavior rather than operational artifacts.

---

## 📈 Core Business KPIs

| Metric                  | Value             | Business Impact                                        |
| ----------------------- | ----------------- | ------------------------------------------------------ |
| **Total Clean Revenue** | **$8,899,501.54** | Validated retail turnover after audit                  |
| **Average Order Value** | **$480.22**       | Anchor metric for high-value targeting                 |
| **Retention Rate**      | **65.58%**        | Indicates a durable and monetizable customer base      |
| **VIP Customers**       | **434**           | Top 10% generating a disproportionate share of revenue |
| **Core Products**       | **810 SKUs**      | ~22% of catalog driving 80% of sales                   |

---

## 💡 Strategic Insights & Executive Actions

### 1. Retention as the Primary Revenue Engine

A **65.58% retention rate** signals that the business is sustained by a loyal, high-LTV customer core.

**Insight:**
Returning customers materially outperform one-time buyers in lifetime value, creating a predictable revenue stream.

**Strategic Action:**
Reallocate **15–20% of acquisition spend** toward VIP retention programs, lifecycle marketing, and personalized offers.

👉 Expected effect: higher marketing ROI and more stable cash flow.

---

### 2. Pareto Inventory & Working Capital Efficiency

Only **810 products** generate **80% of total revenue**, while thousands of long-tail SKUs contribute minimally.

**Insight:**
Excess stock in slow-moving items ties up working capital, suppresses cash flow, and increases holding risk.

**Strategic Action:**

* Automate replenishment for the Core 810
* Gradually liquidate long-tail inventory
* Shift forecasting toward demand-weighted purchasing

👉 Expected effect: improved inventory turnover and stronger capital efficiency.

---

### 3. Outlier Exposure & Revenue Concentration Risk

A single **$168,469** transaction (`PAPER CRAFT, LITTLE BIRDIE`) revealed an unstructured wholesale dependency.

**Risk:**
Losing this client alone could reduce annual revenue by nearly **2%**, highlighting concentration vulnerability.

**Strategic Action:**

* Formalize the relationship via wholesale contract
* Diversify the B2B pipeline
* Introduce account-based management for large buyers

👉 Goal: convert transactional spikes into predictable enterprise revenue.

---

### 4. Seasonality & Capacity Planning

Revenue trends show a pronounced spike in **November**, confirming strong holiday dependence.

**Insight:**
Q4 performance is likely the primary determinant of annual results.

**Strategic Action:**

* Scale inventory and fulfillment capacity by **September**
* Front-load marketing campaigns
* Stress-test logistics before peak demand

👉 Expected effect: maximize peak-period revenue while avoiding operational bottlenecks.

---

## 📂 Project Structure

* `ecomm_sales_analysis1-6.ipynb` — Iterative analytical development
* `ecomm_sales_analysis7.ipynb` — Master notebook with production-ready logic and visualizations
* `final_week1_report.png` — Executive dashboard summarizing key findings


