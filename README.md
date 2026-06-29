# Amazon BodyM - Anthropometric & Mass Scaling Analysis

This repository contains the exploratory data analysis (EDA) and biological proportion tracking completed as part of the **Udacity AWS AI Practitioner Challenge**. The project leverages automated AI tools to extract structural dimensions and correlation matrices from real-world human measurement datasets.

## 📊 Key Insights & Analytics
* **Gender Baseline:** Mapped a baseline physical split across 2,505 subjects where male cohorts average ~176.17 cm in height and ~80.35 kg in weight, compared to female averages of ~163.24 cm and ~66.35 kg.
* **Torso Mass Allocation:** Discovered that total body weight correlates most aggressively with the central trunk—specifically **Chest Girth ($r = 0.915$)** and **Waist Girth ($r = 0.913$)**, isolating them as prime indicators for mass scaling.
* **Proportional Height Variance:** Proved that leg-to-height structural ratios change as vertical height increases (shifting from 45.17% in shorter demographics up to 45.75% in taller demographics), indicating that human vertical gains derive disproportionately from limb elongation rather than the torso.

## 📁 Repository Structure
* `PartyRock_BodyM_Analysis.csv`: Re-engineered analytical matrix sorting baseline metrics and structural correlation values.
* `Body Measurements Analysis.docx`: Final comprehensive project report mapping full methodology and outcomes.

## 🛠️ Skills Demonstrated
* Cloud-driven Data Analysis
* Exploratory Data Analysis (EDA)
* Anthropometric/Biological Statistical Modeling
