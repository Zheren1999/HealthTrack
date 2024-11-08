# HealthTrack
HealthTrack is a comprehensive system designed to streamline hospital patient care management. It effectively handles both inpatient and outpatient care, providing tools for observation status assessment, financial analysis, and insurance integration to support informed decision-making and optimal treatment delivery.


## Introduction

Within the framework of hospital systems, patient care can be broadly categorized into two main streams: inpatient and outpatient care. Each stream caters to distinct medical needs and treatment modalities, shaping the approach to healthcare delivery.

Inpatient care encapsulates individuals who require extended stays within a hospital setting, often undergoing intricate procedures or facing severe health conditions that demand continuous monitoring and treatment. Complex surgeries, critical illnesses, childbirth, and severe injuries constitute scenarios where patients fall under the umbrella of inpatient care. Conversely, outpatient care represents services that do not necessitate hospitalization, enabling patients to receive required treatments or procedures externally without a prolonged hospital stay.

One of the pivotal tasks for physicians lies in determining the observation status of a patient, evaluating the necessity of hospitalization. This assessment period typically spans no more than 24 hours and significantly influences subsequent care decisions. Outpatient care encompasses a spectrum of services ranging from diagnostic procedures like X-rays, MRIs, CT-scans, and lab tests to routine physical exams and radiation treatments.

A notable divergence between inpatient and outpatient care surfaces in their financial implications. Inpatient care often incurs additional facility-based fees, whereas outpatient care primarily involves fees associated with doctors and conducted tests. The cost disparities within healthcare services, as reflected in the Healthcare Cost and Utilization Project data from the Agency for Healthcare Research and Quality, elucidate the variance in average inpatient charges contingent upon treatment duration and complexity. However, the precise financial impact is subject to the terms outlined by insurance providers.

Understanding the nuances between these care models not only aids in providing optimal treatment but also elucidates the financial landscape of healthcare services, contributing to informed decision-making for both patients and healthcare providers.

## Data Description 

The foundation of this project's analysis lies in data collected from the Medicare Inpatient Hospitals by Geography and Service for the year 2021. The dataset comprises essential categories for both inpatient and outpatient care, offering a detailed perspective on healthcare services and their financial implications.

## Features

- **Inpatient Care Management:** Track and manage patients requiring extended hospital stays, including treatment plans, monitoring schedules, and critical care documentation.
- **Outpatient Care Management:** Manage patients receiving treatments without hospitalization, including appointment scheduling, diagnostic tests, and follow-up procedures.
- **Observation Status Assessment:** Tools for physicians to evaluate and determine the necessity of hospitalization within a 24-hour observation period.
- **Financial Analysis:** Compare financial implications of inpatient vs. outpatient care, aiding in cost-effective decision-making for both healthcare providers and patients.
- **Insurance Integration:** Incorporate insurance terms and conditions to provide precise financial impact analyses based on individual patient policies.

## Project Goals

The goal of this project is to conduct an analysis of both inpatient and outpatient care services. The primary focus is to uncover insights regarding the differences between inpatient and outpatient care across various states. Additionally, the analysis aims to identify the most frequently used procedures in these care services. Lastly, the project includes findings related to the providers with the lowest costs for both inpatient and outpatient care.


## Conclusions 

This project's analysis sheds light on the aspects between inpatient and outpatient care services across different states.

- Average cost of Inpatient procedures higher in 50 times that outpatient care in each state.
- The lowest oupatient average cost is in Mississipi (238 dollars), the highest oupatient average cost is in New Jersey (316 dollars). The highest inpatient average cost is in Alaska state (15274 dollars), the lowest inpatient average cost in Alabama (8228 dollars).
- The number of services for Inpatient care is less than for Outpatient care for each state (smoothly decrease from 0.18 up to 0.02)
- The top procedures across all the states are: Level III Diagnostic and Screening Ultrasound,  Level II Echocardiogram Without Contrast,  Magnetic Resonance Imaging and Magnetic Resonance Angiography without Contrast   
