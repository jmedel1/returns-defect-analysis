# Bulk Returns Defect Analysis (Mock Project)

This project uses Excel to track and analyze common return defects for large bulk items like furniture. It’s inspired by real workflows from my Amazon fulfillment center and was created to help build practical skills for a data analyst role in ICQA or Quality.

## What's Included

- Sample data for 30+ bulk item returns including:
  - Product names (e.g., sofas, treadmills, pool sets)
  - Defect types like Damaged, Missing Parts, or Used Item Returned
  - Item counts and resolution times
- A calculated column for **Minutes Per Item**
- A separate `ItemCategories` sheet used to classify products by category (e.g., Furniture, Outdoor, Electronics)
- A `VLOOKUP` function to dynamically assign categories based on item name
- PivotTables to summarize:
  - Total defects by type
  - Average resolution time by item
- Clustered column charts visualizing key trends (now moved to their own chart sheet)

## Sheet Overview

- `Returns Data` — Raw defect data with calculated fields and VLOOKUP
- `ItemCategories` — Lookup table linking item names to categories
- `Pivot - Defects by Type` — Summary of item counts by defect type
- `Pivot - Resolution by Item` — Summary of average resolution time
- `Chart - Defects by Type` — Column chart showing most frequent defect types

## Tools Used

- Microsoft Excel
  - PivotTables
  - VLOOKUP
  - Formulas
  - Clustered column charts
  - Multi-sheet workbook structure

## Why I Made This

I created this as a self-learning project while preparing to apply for an internal Data Analyst position at Amazon. It helped me strengthen Excel skills and simulate real-world defect analysis scenarios used by ICQA and Quality teams.

## Resume Link

This project is referenced in my resume. [View the Excel File](./Bulk_Returns_Analysis_Project.xlsx)
