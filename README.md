# Advertising Effectiveness Case Study: Interaction Modeling, Model Selection & Data Augmentation

> Analyzed the combined impact of TV, Radio, and Newspaper advertising on sales using interaction modeling, train-test validation, and data augmentation to identify the most generalizable predictive model.

**Author:** Amisha Farhana Shaik  
**Project Type:** Business Analytics Case Study | Predictive Modeling | Model Evaluation  

---

## Business Problem

A marketing team wants to understand how combinations of advertising expenditures (TV, Radio, Newspaper) influence product sales.

Key questions:

- Do media channels interact with each other?
- Which combination of predictors best explains sales?
- How do interaction terms affect generalization performance?
- Can data augmentation improve model robustness?

---

## Dataset

- Source: Advertising.csv  
- Predictors:
  - TV advertising spend
  - Radio advertising spend
  - Newspaper advertising spend
- Target:
  - Sales (units)

---

## Modeling Strategy

### 1️⃣ Interaction Terms

Constructed higher-order predictors:

- TV × Radio  
- TV × Newspaper  
- Radio × Newspaper  
- TV × Radio × Newspaper  

Purpose:
To capture non-additive relationships and combined media effects.

---

### 2️⃣ Train-Test Evaluation

Used multiple test sizes:
