This project is a hands-on simulation of SAP Integrated Business Planning (IBP) concepts using Microsoft Excel. It demonstrates core supply chain planning logic including demand forecasting, inventory replenishment, and regional demand decomposition—all without direct access to SAP software.

🔍 Key Features
📈 Forecast Accuracy Tracking
Calculated MAPE (Mean Absolute Percentage Error) and RMSE (Root Mean Squared Error) to evaluate forecast performance.

Simulated a rolling forecast update by averaging the past 3 weeks of actual sales.

Measured and interpreted forecast bias to detect systemic over/underestimation.

📊 Demand Trend Analysis
Used linear regression to identify upward/downward sales trends by product-location.

Provided visual and statistical insights into demand patterns over Q3.

🔁 Inventory Replenishment Logic
Developed reorder point logic: Target Inventory - Inventory Projection.

Triggered planned orders when the reorder point exceeded zero.

Designed a clear flowchart representing replenishment decision logic.

📍 Location-Based Demand Decomposition
Calculated location share of product-level demand (e.g. 49% East, 51% West).

Simulated SAP IBP's location-based disaggregation to support regional planning.

🧠 Concepts Simulated
Rolling forecast updates

Forecast accuracy KPIs (MAPE, RMSE, Bias)

Inventory trigger and order logic

Location-level demand breakdown

Visual dashboards and trend charts

📂 Files Included
SAP_IBP_Excel_Simulation.xlsx — core simulation and logic

SAP_IBP_Simulation.pdf — slide deck overview of the project

replenishment_flowchart.png — visual logic flowchart for Slide 8
