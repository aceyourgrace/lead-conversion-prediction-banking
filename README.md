# lead-conversion-prediction-banking
Predicting high-value leads and CLTV for banks using Python and Tableau


# AI-Powered Lead Conversion Prediction for Banks

Predicting high-value customer conversions and Customer Lifetime Value (CLTV) to enable smarter, data-driven marketing strategies in the banking sector. This project combines Python, machine learning, and Tableau to provide actionable insights for marketing and financial stakeholders.

---

## Project Objective

Banks often struggle to identify which channels bring high-value leads, which leads are most likely to convert, and how much revenue each new customer could generate over time.  

This project demonstrates how predictive modeling and visualization can:

- Identify the most effective acquisition channels.
- Predict a lead’s likelihood to convert.
- Estimate CLTV for potential customers.
- Guide targeted marketing actions to maximize ROI.

---

## Data & Features

The analysis uses anonymized customer lead data with key features including:

| Feature | Description |
|---------|-------------|
| `LeadSource` | Channel through which the lead was acquired |
| `Age`, `Gender` | Demographic information |
| `Income` | Customer income |
| `MaritalStatus`, `Province` | Additional demographic features |
| `InitialProductInterest` | First product the lead showed interest in |
| `WebsiteVisits_PreConversion`, `TimeOnWebsite_Minutes` | Engagement metrics |
| `ConversionFlag` | Whether the lead converted (0/1) |
| `CLTV` | Customer Lifetime Value |

---

## Methodology

1. **Exploratory Data Analysis (EDA) & Feature Engineering**  
   - Understand customer distribution, conversion trends, and CLTV patterns.  

2. **Predictive Modeling**  
   - Random Forest for conversion likelihood prediction.  
   - Linear Regression for CLTV estimation.  

3. **Feature Importance Analysis**  
   - Identify which features most influence conversion and CLTV.  

4. **Tableau Visualization**  
   - Interactive dashboards highlighting key insights across channels, demographics, and predicted outcomes.  

5. **Azure AI Integration (Optional)**  
   - Project designed for cloud deployment via Azure AI, though subscription constraints prevented full deployment.

---

## Key Insights

- **Top conversion drivers:** Referral sources and engagement metrics (e.g., website visits, time on site).  
- **High-CLTV segments:** Not all easy-to-convert leads are the most profitable; some high-value customers need more nurturing.  
- **Channel effectiveness:** Credit Cards and Chequing Accounts show the highest potential conversion when paired with targeted campaigns.  

---

## Tableau Dashboards

- Multiple dashboards showcase the relationships between predicted conversion probability, CLTV, demographics, and product interest.  
- Dashboards are interactive and allow filtering by age, income, and lead source.  
- Interactive Dashboard on Tableau Public: https://public.tableau.com/app/profile/bikesh.chipalu8120/viz/BankingVisualization/Dashboard1

---

## Tools & Technologies

- **Python:** pandas, scikit-learn, matplotlib, seaborn  
- **Machine Learning:** Random Forest, Linear Regression  
- **Data Visualization:** Tableau  
- **Cloud (Planned):** Azure AI services  

---

## Detailed Data Cleaning

If you’d like to explore the **full, in-depth data cleaning workflow** including handling outliers, removing duplicates, correcting spelling errors, and cleaning redundant values and more, you can follow the step-by-step code in this file:  

- BankProject-Data Cleaning in depth.ipynb)

This file provides a comprehensive guide for anyone interested in learning more from the data preprocessing process.
