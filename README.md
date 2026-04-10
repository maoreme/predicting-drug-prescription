# Predicting Drug Prescription Based on Patient Characteristics

## Overview
This project explores how patient characteristics influence drug prescription decisions. The analysis focuses on both demographic and clinical variables, including age, sex, blood pressure, cholesterol, and sodium-to-potassium ratio (Na_to_K).

The goal is to identify which features are most associated with different drug prescriptions and evaluate whether these characteristics can be used to predict treatment choice.

---

## Dataset
The dataset contains patient-level information with the following variables:

- **Age** – Patient age  
- **Sex** – Male or Female  
- **Blood Pressure (BP)** – Low, Normal, or High  
- **Cholesterol** – Normal or High  
- **Na_to_K** – Sodium-to-potassium ratio  
- **Drug** – Prescribed drug category  

---

## Project Objectives
- Explore relationships between patient characteristics and drug prescriptions  
- Identify key variables that distinguish between drug types  
- Compare patterns between Drug X and Drug Y  
- Train a simple decision tree model to support exploratory findings  

---

## Exploratory Data Analysis
The analysis includes multiple visualizations to understand how different variables relate to drug prescription patterns.

Key areas explored:
- Age distribution across drug types  
- Sex distribution across drug types  
- Na_to_K differences between drugs  
- Relationship between blood pressure and Na_to_K  
- Comparison of Drug X vs Drug Y  

---

## Key Findings
- **Na_to_K** shows the strongest separation across drug types and appears to be the most informative variable.  
- **Blood pressure** differs notably between Drug X and Drug Y, despite similar age distributions.  
- **Na_to_K and BP** exhibit a non-linear relationship, with normal BP associated with lower Na_to_K values.  
- **Age** shows variation across drug groups but with overlap, suggesting a weaker role.  
- **Sex** appears relatively balanced across drugs and is not a major influencing factor.  

---

## Predictive Modeling
A simple decision tree model was trained to predict drug type based on patient characteristics.

The model reinforces earlier findings by highlighting:
- **Na_to_K** as a primary splitting variable  
- **Blood pressure** as an additional important factor  

---

## Tools Used
- **R**
- **R Markdown**
- **ggplot2**
- **dplyr**
- **rpart**
- **rpart.plot**

---

## Project Structure
