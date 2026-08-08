# UIDAI Aadhaar Enrolment & Update Analytics

## Project Overview
This repository contains a data analysis project based on Aadhaar enrolment and update data provided through a government data challenge. The objective of the project is to study enrolment trends, update patterns, and regional operational load across states and districts in India.

## Problem Statement
As Aadhaar enrolment reaches saturation, update activities such as demographic and biometric corrections have increased. These updates are unevenly distributed across regions, creating operational pressure in certain states and districts. This project analyses Aadhaar data to identify update-heavy regions, age-group patterns, and potential operational risk areas.

## Dataset
The analysis uses Aadhaar enrolment and update datasets provided through a government data challenge, containing monthly transaction data.

Key fields include:

State and District
Month
Total Enrolments
Demographic Updates
Biometric Updates
Age Group (0–5, 5–17, 17+)

Derived metrics such as update-to-enrolment ratio and updates per 1,000 enrolments are also used.

## Methodology
- Data cleaning and standardisation of geographic fields
- Feature engineering including ratio-based metrics
- Trend and comparative analysis across time and regions
- Identification of high-churn and anomaly districts

## Tools Used
- Power BI for data modelling and visualisation
- Excel / Power Query for preprocessing

## Key Insights

### Overview — Aadhaar Transaction Overview
<img width="940" height="538" alt="image" src="https://github.com/user-attachments/assets/1a24b2b5-34df-46a7-833e-6a6f34c3ce37" />

Analysis:

Aadhaar updates significantly exceed new enrolments, showing that the system is increasingly driven by ongoing maintenance and citizen update activity.
Transaction activity varies across months, indicating periods of relatively higher operational demand.
Enrolments are heavily concentrated in the 0–5 age group (65%), followed by 5–17 (32%) and 17+ (3%).
Aadhaar transactions are concentrated in a few major states, indicating uneven regional service demand.

### Demographics — Demographic Distribution & Update Patterns
<img width="1331" height="740" alt="image" src="https://github.com/user-attachments/assets/4b9086c2-1994-4f01-a8d4-a576498a80af" />
Analysis:
Enrolment is predominantly driven by children, while adult enrolment remains limited.
Demographic updates per 1,000 enrolments are high, indicating substantial post-enrolment update activity.
Demographic update activity varies across months, with increased activity in the later months of the dataset.
High-churn states contribute disproportionately to demographic updates, highlighting regional differences in update demand.

### Updates — Update Load & Risk Identification
<img width="1469" height="737" alt="image" src="https://github.com/user-attachments/assets/9affe8ab-1b6a-4034-9e42-801020392f5a" />
Analysis:

Update-to-enrolment ratios vary substantially across states, showing significant differences in the intensity of update activity.
A limited number of states account for a disproportionately high share of the update load.
10 states are identified as having high update loads.
965 districts are flagged for unusual transaction patterns, providing a basis for further operational monitoring.
Biometric updates contribute the majority of update activity, making them an important component of overall operational demand.

### Biometric — Biometric Operations & Age-wise Performance
<img width="1328" height="739" alt="image" src="https://github.com/user-attachments/assets/23276e06-ab78-4977-818c-155f38fa81da" />

Analysis:

Biometric updates account for approximately 59% of total updates, making them a major component of Aadhaar service activity.
Youth and adult biometric updates are relatively balanced (49% vs 51%).
Month-on-month biometric activity shows considerable fluctuations, indicating periods of changing operational demand.
A limited number of states account for high biometric update loads, suggesting the need for targeted capacity and infrastructure planning.

## Repository Structure
- `data/` – Dataset description files
- `dashboards/` – Power BI dashboard screenshots
- `report/` – Final consolidated PDF report
- `notebooks/` – Analysis notebooks (if applicable)

## Note
The code and dashboards in this repository are shared for academic and analytical purposes. The dataset was provided through a government data challenge and is based on Aadhaar data.
