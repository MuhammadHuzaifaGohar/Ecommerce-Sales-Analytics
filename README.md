# Ecommerce-Sales-Analytics
# 📊 Premium E-Commerce Sales Analytics Dashboard
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.32-FF4B4B?logo=streamlit)
![Plotly](https://img.shields.io/badge/Plotly-Latest-507282?logo=plotly)
![Pandas](https://img.shields.io/badge/Pandas-Data_Processing-150458?logo=pandas)

### 🚀 [Live Interactive Dashboard: View Here](https://ecommerce-sales-analytics-n9exwdzecqejcmv8ngrvne.streamlit.app/)

An advanced, end-to-end **Business Intelligence (BI) application** built to transform raw e-commerce data into actionable executive insights. This interactive Streamlit dashboard provides real-time simulation, KPI tracking, and financial modeling to drive data-backed strategic decisions.

<img width="586" height="462" alt="Analysis" src="https://github.com/user-attachments/assets/c78d3f6c-27ae-4cc4-b6ab-0f1196d3d5a5" />
<img width="636" height="372" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/9af7f707-40df-43ae-bebe-1efc9d345ca8" />

---
 In a competitive e-commerce landscape, delivery performance and customer satisfaction are the primary drivers of retention. This project analyzes **100,000+ Brazilian orders** to identify logistics bottlenecks, measure the impact of shipping delays on review scores, and provide actionable insights for operational improvement.
 
## 🎯 1. Project Scope
The primary objective of this project is to bridge the gap between complex data sets and executive decision-making. The application serves as a **Strategic Growth Simulator** for e-commerce platforms, enabling stakeholders to:
* Monitor baseline revenue and profit margins in real-time.
* Simulate the financial impact of price adjustments and marketing spend.
* Track customer retention penalties and rewards.
* Visualize product category performance and historical sales trends.

---

## 🏗️ 2. Strategic Planning
To ensure high performance, scalability, and an intuitive User Experience (UX), the project was architected with the following tech stack and design principles:

* **Frontend/UI:** Streamlit (Custom CSS injected for a premium, glassmorphism-inspired aesthetic).
* **Data Manipulation:** Python (Pandas, NumPy) for complex feature engineering, Z-score anomaly detection, and array generation.
* **Data Visualization:** Plotly Graph Objects & Express for highly interactive, production-ready charts (Waterfall, Sunburst/Donut, Area Trends).
* **State Management:** Implementation of `@st.cache_data` to ensure rapid data reloading without server latency.

---

## ⚙️ 3. Execution & Engineering
The development pipeline was divided into core analytical modules:

1.  **Data Ingestion & Cleaning:** Automated handling of missing values (median imputation) and outlier removal to ensure a 99%+ data health score.
2.  **Simulation Engine:** Built a custom algorithm taking inputs from sidebar controls (Price Adjustment %, Marketing Spend, Retention Rate) to calculate projected Q4 revenue arrays.
3.  **Visual Architecture:** * Deployed a **Financial Waterfall Chart** to break down the exact dollar impact of distinct business variables.
    * Integrated a **Time-Series Area Chart** using spline interpolation to forecast monthly trajectories.
4.  **Cloud Deployment:** Seamlessly deployed to Streamlit Community Cloud with continuous integration linked directly to the main GitHub branch.

---

## 📈 4. Advanced Analysis
The dashboard moves beyond basic reporting by offering deep-dive analytical features:
* **Revenue Gap Analysis:** Instantly calculates and visualizes the delta between current performance and simulated market scenarios.
* **Category Mix Insights:** Analyzes revenue distribution across premium product lines (e.g., Signature Fragrances, Premium Skincare).
* **Automated Strategy Alerts:** Generates dynamic, text-based strategic recommendations based on user inputs (e.g., alerting the user to required retention rates if prices are hiked).

---

## 🏆 5. Business Outcome
This analytics hub provides immediate ROI value by:
* **Reducing Time-to-Insight:** Stakeholders can test "what-if" scenarios in seconds rather than waiting for static weekly reports.
* **Risk Mitigation:** Visually identifying the exact point where customer churn negates marketing spend prevents costly strategic errors.
* **Data Democratization:** The highly intuitive UI allows non-technical users to engage with complex predictive models effortlessly.
<img width="414" height="162" alt="insights" src="https://github.com/user-attachments/assets/32767f9b-e912-410c-b6fa-a0f6ebe63a80" />

## Finalizing the Narrative
Based on this analysis, the company is risking in revenue due to logistics failures in the Northern states.

### Strategic Action Plan:
**Carrier Diversification:** I recommend a 3-month pilot program with regional third-party logistics (3PL) carriers in identified "High-Delay" hubs to bypass central sorting bottlenecks. NPS Recovery: By reducing regional delays by even 25%, simulation data suggests we can improve the average regional NPS from 3.2 to 4.1.

**Predictive Estimated Delivery Date (EDD):** Implement a dynamic EDD model that adds a 2-day buffer for Northern regions to manage customer expectations and preserve review scores.

---

## 💻 Local Installation & Usage
To run this application on your local machine:

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)


**THANKS!**
