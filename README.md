# Glovo-Marketplace-Profitability-Analysis

## Project Overview

This project was completed as part of a marketplace data analyst business case assessment.
The objective was to analyze store-level profitability and identify structural drivers of margin loss. The focus was not just on GMV, but on contribution, understanding which stores were truly adding value and which were quietly eroding margins.
Rather than analyzing surface-level metrics, I built an order-level contribution framework and store risk prioritization model.

## Business Context

In a marketplace environment, high GMV does not automatically translate to profitability. Delivery cost (CPO), basket size (AOV), and operational inefficiencies significantly impact contribution margin.

The goals of this analysis were to:

- Identify loss-driving stores  
- Quantify unprofitable orders  
- Validate root causes using data  
- Propose an actionable 3-month recovery plan  

---

## What I Built

### Order-Level Contribution Framework

- Commission calculation  
- Platform revenue per order  
- Cost per order (CPO)  
- Contribution per order  
- Unprofitable order flag  

This shifted the analysis from volume-based reporting to margin-based decision-making.

---

### Store Risk Matrix

I developed a prioritization framework using:

- Contribution per order  
- Unprofitable order rate  
- Total store contribution  

Stores were classified into:

- Critical  
- High Risk  
- Moderate  
- Healthy  

This allowed immediate focus on the highest-impact stores.

---

### Root Cause Validation

Instead of assuming drivers, I validated them using correlation analysis:

- Distance → CPO (r = 0.7)  
- AOV → Contribution (r = 0.8)  
- Unprofitable Rate → Contribution (strong negative relationship)  
- Courier waiting time → Minimal impact (r = 0.1)  

This confirmed losses were structural and cost-driven — not demand-driven.

---

## Key Findings

- 5 stores were responsible for most margin pressure  
- 2 stores classified as Critical  
- High delivery distance significantly increased CPO  
- Low AOV stores struggled to cover delivery cost  
- Margin risk was concentrated in a small subset of stores  

---

## Recommendations

### Short-Term (1–2 weeks)
- Reduce delivery radius  
- Enforce Minimum Order Value (MOV)  
- Remove low-margin SKUs  

### Mid-Term (2–6 weeks)
- Improve batching  
- Clean menu structure  
- Introduce AOV-boosting bundles  

**Expected Margin Uplift:** €350–€500 monthly  

---

## Tools Used

- SQL (data aggregation & validation)  
- Excel (pivot modeling & contribution framework)  
- Correlation analysis  
- Business risk prioritization framework  

---

## Why This Project Matters

This project demonstrates:

- Marketplace unit economics understanding  
- Contribution-first thinking  
- Data-backed root cause validation  
- Structured prioritization  
- Actionable business recommendations  

Analytics should drive decisions — not just dashboards.
