# 🌿 Case Study: CO₂ Dashboard for Freight Emissions Visibility

## 📌 Overview  
As companies face mounting pressure to track and reduce carbon emissions, our logistics clients lacked clear visibility into CO₂ footprints across their global shipments. I led the end-to-end product delivery of a **CO₂ Emissions Dashboard**, designed to quantify savings, identify inefficiencies, and support data-driven decision-making.

---

## 🎯 Goal  
To enable clients to track and reduce their shipment-related emissions by:  
- Visualizing **CO₂ savings vs. baseline**  
- Tracking mode-based emissions (Air, Ocean, Road)  
- Detecting anomalies and missed optimization opportunities  
- Supporting **monthly reporting** and **KPI alignment**

---

## 👨‍💻 My Role  
**Product Manager – Data Products**  
- Defined product requirements and visualization goals  
- Collaborated with data engineers, dashboard developers, and stakeholders  
- Owned end-to-end delivery from discovery to launch

---

## 🧩 Problem  
Clients received ad-hoc freight data with no centralized system to:  
- Measure emissions across modes and lanes  
- Compare "as-is" vs. optimized shipment strategies  
- Identify hotspots of inefficiency  
- Report validated emissions to ESG teams and executives

---

## 🚀 Solution  
We built a **dynamic Power BI dashboard** powered by PostgreSQL and SeaRoutes API that included:

| Feature                          | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| 📊 **Savings Heatmap**           | Showed CO₂ and cost savings per consignee and route                        |
| 🔄 **Baseline Comparison**       | Compared actual vs optimized tonne-km and emissions                        |
| 🚨 **Anomaly Detection**         | Flagged outlier shipments exceeding emission thresholds                    |
| 📅 **Monthly Reports**           | Auto-generated PDFs for monthly emissions tracking                         |
| 🌍 **API-Driven Estimation**     | Integrated SeaRoutes API for multi-leg route emissions                     |
| 🛠 **Mode & Route Filters**      | Interactive filters by mode, shipper, consignee, region, and hub           |

---

## 🔧 Tools Used  
- **Power BI** – Visualizations, filters, heatmaps  
- **SeaRoutes API** – Emissions estimation (radiative forcing, distance, tonnage)  
- **Google Maps API** – City/ZIP to airport/country fallback logic  
- **PostgreSQL** – Raw + processed freight data  
- **Azure Data Factory** – Weekly data ingestion and transformation

---

## 📊 Impact  
- ♻️ Identified **10–18% CO₂ savings potential** across top air lanes  
- 📉 Reduced reliance on air freight for short-haul destinations  
- 🧠 Created a **standardized reporting framework** adopted by 3 clients  
- 🕒 Saved 6+ hours/week of manual data validation and formatting

---

## 📷 Screenshots (Optional)
> Add dashboard screenshots or GIFs here showing:  
> - Savings heatmap  
> - Emissions breakdown by mode  
> - Monthly summary view

---

## 🗣 Stakeholder Feedback  
> “This dashboard is the missing piece in our ESG strategy. It not only tells us where we’re inefficient — it tells us what to do next.”  
> — Global Logistics Director, Fortune 500 client

---

## 🧠 Lessons Learned  
- CO₂ estimation is **as much a data quality challenge** as a modeling one.  
- Shipping modes and routes are complex — fallback logic is critical.  
- Simple, intuitive visualizations > complex charts for executive adoption.  
- Stakeholders value **auditability and consistency** above all in emissions tracking.

---

## 📁 Related Repos  
- 🔗 [SeaRoutes Integration Module](#) *(optional)*  
- 🔗 [Weekly ADF Pipeline Scripts](#) *(optional)*  
