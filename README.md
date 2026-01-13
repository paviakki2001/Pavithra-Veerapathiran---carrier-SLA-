🚚 SLA Breach Prediction — Logistics Analytics Project

This project focuses on identifying and understanding Service Level Agreement (SLA) breaches in logistics operations using structured data analysis. The goal is to detect where delays happen, why they happen, and how they can be predicted and prevented using data-driven insights.

📌 Business Problem

A Service Level Agreement (SLA) defines the delivery timeline promised to customers.
An SLA breach occurs when shipments are delivered later than committed.

SLA breaches lead to:

Financial penalties

Customer dissatisfaction

Operational inefficiencies

Reputation damage

Predicting and preventing SLA breaches allows logistics companies to:

Improve service reliability

Optimize carrier selection

Reduce cost overruns

Proactively manage risk

📂 Project Structure
📁 SLA_Breach_Prediction/
│
├── 📄 b2b_sla_logistics_dataset_200k.csv        → Raw dataset  
├── 📓 Week1_SLA_Data_Preprocessing.ipynb       → Data cleaning & validation  
├── 📄 Week1_SLA_Executive_Report.docx          → Business & data readiness report  
├── 📓 week2_eda.ipynb                          → Exploratory Data Analysis  
├── 📄 Week2_EDA_Executive_Report.docx          → EDA insights & interpretation  

🧩 Phase 1 — Data Preparation (Week 1)

Week 1 focused on creating a trustworthy, production-ready dataset.

The objective was to clean, validate, and prepare data without introducing bias or artificial accuracy.
No modeling or visualization was done at this stage.

What was done

Duplicate removal

Missing value handling

Invalid record removal

Target variable creation (sla_breach_flag)

Data consistency validation

The result is a fully cleaned and validated dataset ready for EDA and modeling.

📄 Executive Summary from Week 1 

Week1_SLA_Executive_Report (1) …

🔍 Phase 2 — Exploratory Data Analysis (Week 2)

Week 2 focused on answering the question:

“Where and why do SLA breaches happen?”

This phase analyzed the cleaned dataset without building any models.

Key EDA Objectives

Identify high-risk carriers, routes, and shipping modes

Compare cost vs reliability

Analyze shipment characteristics

Study correlation between variables

Key Findings

From the EDA report 

Week2_EDA_Executive_Report

:

SLA breaches are concentrated among specific carriers and routes

Certain shipping modes show higher delay variability

Higher shipping cost does NOT guarantee lower SLA breach risk

Priority and fragile shipments show different risk patterns

Delivery delay days strongly correlate with SLA breach flag

📊 Business Interpretation

Operational factors such as:

Carrier performance

Route reliability

Transport mode

have more impact on SLA risk than cost alone.

This means organizations should:

Focus on operational optimization

Not assume premium pricing ensures reliability

Use data-driven carrier and route selection

These insights directly guide feature selection and model design in the next phase.

🎯 End Goal of This Project

By combining:

Clean data (Week 1)

Deep EDA insights (Week 2)

Predictive modeling (Week 3+)

The final system will:

Predict SLA breaches in advance

Identify high-risk shipments

Enable proactive logistics planning

🧑‍💻 Author

Pavithra Veerapathiran
Data Scientist Trainee
📍 Chennai, India
🔗 LinkedIn

🔗 GitHub
