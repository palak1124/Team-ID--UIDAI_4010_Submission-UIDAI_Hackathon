# Team-ID--UIDAI_4010_Submission-UIDAI_Hackathon

# Aadhaar Enrolment and Update Analysis

## Project Overview
This repository contains a data analysis project based on Aadhaar enrolment and update data published by the Unique Identification Authority of India (UIDAI). The objective of the project is to study enrolment trends, update patterns, and regional operational load across states and districts in India.

<img width="940" height="538" alt="image" src="https://github.com/user-attachments/assets/1a24b2b5-34df-46a7-833e-6a6f34c3ce37" />

## Problem Statement
As Aadhaar enrolment reaches saturation, update activities such as demographic and biometric corrections have increased. These updates are unevenly distributed across regions, creating operational pressure in certain states and districts. This project analyses Aadhaar data to identify update-heavy regions, age-group patterns, and potential operational risk areas.

## Dataset
The analysis uses UIDAI Aadhaar enrolment and update datasets with monthly transaction data.
Key fields include:
- State and District
- Month
- Total Enrolments
- Demographic Updates
- Biometric Updates
- Age Group (0–5, 5–17, 17+)

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
- Aadhaar updates significantly exceed new enrolments, indicating a maintenance-driven system.
- Enrolments are concentrated in the 0–5 age group, with minimal adult enrolment.
- A small number of states contribute a large share of total updates.
- Biometric updates form the majority of update transactions.

## Repository Structure
- `data/` – Dataset description files
- `dashboards/` – Power BI dashboard screenshots
- `report/` – Final consolidated PDF report
- `notebooks/` – Analysis notebooks (if applicable)

## Note
The code and dashboards in this repository are shared for academic and analytical purposes. Original data is sourced from UIDAI.
