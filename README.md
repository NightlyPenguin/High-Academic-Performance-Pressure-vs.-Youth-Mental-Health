# CDC YRBSS Youth Mental Health & Academic Performance Analysis

## Overview
This project processes and analyzes microdata from the CDC's **Youth Risk Behavior Surveillance System (YRBSS)** to investigate the relationship between academic achievement/pressure, sleep duration, and self-reported mental health outcomes (persistent sadness and suicidal ideation) among high school students.

## Key Features
- **Automated Data Pipeline:** Cleans and recodes raw YRBSS ASCII/CSV survey exports.
- **Demographic & Outcome Recoding:** Standardizes binary mental health indicators, grade categories, and sleep metrics.
- **Survey Weight Preservation:** Retains complex sampling weights (`weight`, `stratum`, `psu`) for nationally representative statistical modeling.

## Repository Structure
