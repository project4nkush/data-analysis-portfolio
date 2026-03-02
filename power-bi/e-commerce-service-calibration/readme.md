Service-Level Calibration & Risk Modeling in E-Commerce Logistics
Objective

Evaluate whether the company’s 24.5-day delivery promise is appropriately calibrated and identify operational drivers of late deliveries.

The analysis focuses on percentile-based reliability, policy sensitivity, and variance decomposition across shipment size and geography.

Tools & Methods

Power BI

Relational Data Modeling

DAX Measures

Percentile Analysis (P90, P95)

Policy Sensitivity Simulation

Variance Decomposition (Size × Geography)

Data Model

Constructed a structured model linking:

Customers → Orders

Orders → OrderItems

Products → OrderItems

Created calculated fields:

Product Volume

Size Buckets (percentile-based segmentation)

Actual Delivery Days

Built dynamic measures:

Avg Actual Delivery (Delivered Only)

Avg Estimated Delivery

Late %

P90 Delivery

Late % under alternative promise scenarios

Key Findings

Avg Estimated Delivery: 24.5 days

Avg Actual Delivery: 12.4 days

Late Rate: 6%

P90 Delivery: 23 days

The delivery promise is calibrated near the 90th percentile of actual performance, suggesting intentional reliability targeting.

Reducing the promised delivery time to 20 days would increase late deliveries from 6% to 13%, more than doubling reliability risk.

Shipment size materially affects variability:

Bulky items show higher delivery times and late rates.

Geographic analysis reveals amplified tail risk in specific states (e.g., BA, ES, RJ), indicating regional logistics constraints rather than uniform systemic inefficiency.

Strategic Insight

The system appears calibrated around a ~90% service reliability threshold.

Meaningful reduction in promised delivery time would require operational variance reduction, particularly for large-volume shipments in high-risk regions.

Policy adjustments alone are insufficient without addressing tail-risk drivers.

<img width="1277" height="715" alt="image" src="https://github.com/user-attachments/assets/30958c25-f274-4f5d-b0cd-a27322e07bfc" />
<img width="1271" height="715" alt="image" src="https://github.com/user-attachments/assets/35582011-1d31-4a3e-ae03-6bfa161bf2ae" />
<img width="1274" height="716" alt="image" src="https://github.com/user-attachments/assets/4ea62338-d169-4494-9880-5b836bcfae20" />
