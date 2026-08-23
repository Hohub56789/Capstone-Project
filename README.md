Predicting Diabetes Risk from Health Indicators
This project is part of my capstone work, where I explore whether basic health and lifestyle indicators can help identify people who are at higher risk of diabetes. The goal is early screening, not clinical diagnosis.

Project Overview
This repository contains the first phase of the project, focused on understanding and exploring the CDC Diabetes Health Indicators dataset. 

Business Problem
Diabetes is common, expensive, and often detected too late. If we can use simple health and lifestyle information to flag higher‑risk individuals earlier, screening and prevention can be targeted more effectively.

Data Science Problem
I frame this as a binary classification problem:

0 = no diabetes

1 = prediabetes or diabetes

The dataset merges prediabetes and diabetes into one class and doesn’t distinguish between type 1 and type 2. Most indicators relate more to type 2 risk, so that’s the practical framing.

Key question:

How well can features like BMI, blood pressure, cholesterol, general health, physical activity, and demographics predict diabetes risk?

Dataset
Source: CDC BRFSS 2015 (UCI Machine Learning Repository)
Rows: 253,680
Features: 21 predictors
Target: Diabetes_binary

Variables include medical conditions, lifestyle factors, healthcare access, self‑reported health, demographics, and BMI.
Note: BRFSS is a weighted survey, but this project uses raw sample proportions.

Stakeholders
Public health organisations
Clinicians
Health insurers and policy planners
Digital health app developers
Individuals wanting to understand risk factors
