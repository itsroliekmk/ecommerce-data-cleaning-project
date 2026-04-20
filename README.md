# 🛒 E-Commerce Data Cleaning Project

![Status](https://img.shields.io/badge/Project-Completed-success) ![Tools](https://img.shields.io/badge/Tools-Data_Standardization-blue)

## 📌 Executive Summary
This project demonstrates the transformation of a "dirty" e-commerce dataset into a standardized, analysis-ready format. I resolved over **100+ data entry inconsistencies** across logistics, payments, and product categories.

---
# 🛠️ Data Quality & Standardization Portfolio

## 📝 Comprehensive Data Audit & Cleaning
I performed a deep-cleaning of 500+ records, focusing on multi-field standardization and structural integrity.

### 🔄 The "Before & After" Comparison

| Data Field | Messy (Input) | Standardized (Output) | Cleaning Task Performed |
| :--- | :--- | :--- | :--- |
| **Logistics** | `DHL Nig`, `D.H.L`, `dhl` | ✅ **DHL** | Categorical Unification |
| **Dates** | `22/06/23`, `Jun-22-23` | ✅ **2023-06-22** | **ISO 8601 Normalization** |
| **Locations** | `Lagoss`, `Lagos (Nig)` | ✅ **Lagos** | **Geographic Scrubbing** |
| **Headers** | `Order Date`, `Prod Cat` | ✅ **order_date**, **prod_cat** | **Snake_Case Conversion** |
| **Payments** | `*737*`, `ussd`, `Xfer` | ✅ **USSD / Transfer** | Technical Code Mapping |
| **Integrity** | 58 Blank Records | ✅ **0 Blanks** | **Completeness Audit** |

---

## 🛠️ Detailed Methodology
1. **Date Normalization**: Re-formatted mixed date strings into a single professional standard (`YYYY-MM-DD`) to prevent system errors.
2. **Location Scrubbing**: Manually audited location fields to fix regional typos and ensure consistent city names.
3. **Snake_Case Formatting**: Converted all column headers to lowercase with underscores, making the file ready for SQL/Database imports.
4. **Logic Mapping**: Used advanced mapping to group over 130 variations of vendor and category names into a clean "Master List."

## 🛠️ The Problem
The raw data contained significant noise, making accurate reporting impossible:
* **Redundant Labels:** `Home`, `Homee`, and `HOME` were treated as 3 different categories.
* **Typos:** Errors like `Fashon` and `Foood` created inaccurate sales totals.
* **Mixed Formats:** Logistics partners had multiple names (e.g., `DHL Nig` vs `DHL`).

---

## 📊 Key Results
By applying a standardization framework, I improved data quality significantly:

| Metric | Before Cleaning | After Cleaning | Improvement |
| :--- | :---: | :---: | :---: |
| **Total Unique Labels** | 130 | **28** | **-78% Noise** |
| **Product Categories** | 50 | **10** | **Cleaned** |
| **Logistics Partners** | 38 | **7** | **Cleaned** |

---

## 🧪 My Cleaning Process

### 1. Audit & Discovery
I identified all unique variants using data exploration to map out every spelling error and formatting inconsistency.

### 2. Standardization Logic
I created a mapping system to unify labels:
* **Logistics:** Unified 38 names into 7 official partners (GIG, DHL, etc.).
* **Payments:** Converted codes like `*737*` and `Xfer` into `USSD` and `Bank Transfer`.

### 3. Data Refinement
* Removed hidden whitespaces.
* Normalized text casing (UPPER/Lower/Sentence).
* Validated category assignments.

---

## 🛠️ Detailed Methodology
1. **Date Normalization**: Re-formatted mixed date strings into a single professional standard (`YYYY-MM-DD`) to prevent system errors.
2. **Location Scrubbing**: Manually audited location fields to fix regional typos and ensure consistent city names.
3. **Snake_Case Formatting**: Converted all column headers to lowercase with underscores, making the file ready for SQL/Database imports.
4. **Logic Mapping**: Used advanced mapping to group over 130 variations of vendor and category names into a clean "Master List."

## ✅ Business Value
The dataset is now **100% ready** for Power BI, Tableau, or Excel reporting. Stakeholders can now view accurate performance metrics without the risk of duplicate or missing data.
