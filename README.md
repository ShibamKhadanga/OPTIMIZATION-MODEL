# Task 4: OPTIMIZATION MODEL
**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: SHIBAM KHADANGA

**INTERN ID**: CT04DF1351

**DOMAIN**: Data Science

**BATCH DURATION**: Jun 5th, 2025 to July 5th, 2025

**MENTOR NAME**: NEELA SANTHOSH

This task is part of the CODTECH Data Science Internship.

## 📌 Objective

Solve a real-world business problem using **Linear Programming** and the **PuLP** library in Python.

## 🧠 Problem Statement

**Diet Optimization Problem**:  
Select quantities of two food items (e.g., Chicken and Beef) that:

- Maximize nutritional value (protein, etc.)
- Stay within budget and dietary constraints (e.g., calories, fat)

## 🔧 Tools & Libraries

- `pulp`: for modeling and solving linear programs

## ✅ Model Description

We define:

- Decision variables: quantities of `Chicken (x1)` and `Beef (x2)`
- Objective function: Maximize nutrition → `30*x1 + 20*x2`
- Constraints:
  - **Fat limit**: `2*x1 + 3*x2 ≤ 10`
  - **Cost limit**: `x1 + 2*x2 ≤ 8`

## 📄 OUTPUT
![Image](https://github.com/user-attachments/assets/cc7c1aee-046d-4362-a87f-bb68332cf5e3)
