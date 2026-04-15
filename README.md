# Quantium Retail Analytics

A retail analytics project focused on **customer segmentation**, **category performance**, and **trial store uplift assessment** for the chips/snack foods category.

This project was completed as a business-focused analytics case study using **Python**, **Pandas**, and **PowerPoint-style reporting**, with emphasis on translating raw transactional data into actionable commercial insights.

---

## Project Overview

The project is divided into three parts:

### Task 1 — Category Review and Customer Analytics
- Cleaned and validated transaction and customer data
- Analysed purchasing behaviour across customer segments
- Identified commercially valuable shopper groups using:
  - total sales
  - purchase frequency
  - basket size
  - average price per unit
- Developed recommendations for customer targeting and category strategy

### Task 2 — Experimentation and Uplift Testing
- Built monthly store-level performance measures
- Selected matched control stores for trial stores using pre-trial similarity
- Compared actual versus expected performance during the trial period
- Assessed uplift in both sales and customer counts
- Evaluated the relative strength of trial evidence across stores

### Task 3 — Analytics and Commercial Application
- Converted analytical findings into a client-style presentation
- Summarised key business insights for category and store strategy
- Provided recommendations on customer targeting, layout rollout, and next-step testing

---

## Business Questions

This project addresses the following questions:

1. Which customer segments are the most valuable in the chips category?
2. What behavioural differences exist across lifestage and affluence groups?
3. Did the store trial generate measurable uplift versus a matched control store?
4. Which trial stores provide the strongest evidence for rollout?
5. What commercial actions should be recommended based on the analysis?

---

## Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**
- **PowerPoint / presentation reporting**

---

## Key Analytical Methods

- Data cleaning and validation
- Feature engineering
- Customer segmentation analysis
- Monthly KPI construction
- Control-store matching
- Baseline scaling
- Trial uplift assessment
- Business reporting and presentation design

---

## Key Findings

### Customer and Category Insights
- `OLDER FAMILIES - Budget` and `OLDER FAMILIES - Mainstream` were identified as the strongest value-driving customer groups
- `YOUNG SINGLES/COUPLES - Mainstream` showed higher average price per unit, suggesting stronger price tolerance
- Family-oriented segments contributed strongly through volume and basket size

### Trial Store Insights
- **Store 77** showed the clearest and strongest uplift
- **Store 86** showed positive evidence, with stronger uplift in customer counts than in sales
- **Store 88** showed positive uplift, but the result should be interpreted more cautiously due to a weaker control-store match

---

## Repository Structure

```text
quantium-retail-analytics/
├── data/
│   └── QVI_data.csv
├── notebooks/
│   ├── task1_customer_analytics.ipynb
│   └── task2_experimentation_uplift_testing.ipynb
├── reports/
│   ├── task1_customer_analytics.html
│   ├── task3_presentation.pptx
│   └── task3_presentation.pdf
├── images/
│   └── charts_and_outputs/
└── README.md
