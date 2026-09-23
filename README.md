# Excel Assignment 1 – Data Exploration

## Project Title
Excel Assignment 1 – Data Exploration on the Product Dataset

## Overview
This project performs foundational data exploration and analysis in Microsoft Excel
on a **Product Dataset** (30 records) with the attributes: Product ID, Product Name,
Brand Name, Quantity, Category, and Price. It applies data summarization, logical
classification, conditional aggregation, and text-extraction functions to prepare the
data for further analysis.

## Objectives
- Practice foundational Excel functions used in real-world data analysis.
- Summarize numerical data with SUM, COUNT, AVERAGE, MIN, and MAX.
- Classify records using logical (IF) conditions.
- Aggregate data conditionally using SUMIF and COUNTIF.
- Extract structured information from text fields using LEFT, MID, and RIGHT.

## Dataset
`product_dataset_raw.csv` — the raw Product Dataset used for the analysis (30 rows,
6 columns: Product ID, Product Name, Brand Name, Quantity, Category, Price).

The **Product ID** follows the pattern `DD-MMM-CC`, e.g. `05-JAN-US`:
| Segment | Meaning | Example |
|---|---|---|
| First 2 characters | Day | `05` |
| Characters 4–6 | Month | `JAN` |
| Last 2 characters | Country Code | `US` |

## Tasks Performed
1. **Sum, Count, Average** — Total price, number of products, and average price of
   all products using `SUM`, `COUNT`, `AVERAGE`.
2. **Minimum and Maximum** — Lowest and highest product price using `MIN` and `MAX`.
3. **Logical Function (IF)** — A new `Price Range` column classifies each product as
   `High Price` (Price ≥ $500) or `Standard Price` (Price < $500).
4. **Conditional Functions (SUMIF / COUNTIF)** — Total price of all Electronics
   products (`SUMIF`) and count of products priced below $100 (`COUNTIF`).
5. **Text Formatting (LEFT / RIGHT / MID)** — Three new columns extracted from
   Product ID: `Day` (`LEFT`), `Country Code` (`RIGHT`), and `Month` (`MID`).

## Files in this Repository
| File | Description |
|---|---|
| `Excel_Assignment1_Data_Exploration.xlsx` | Solution workbook with formulas, calculated results, and newly created columns |
| `product_dataset_raw.csv` | Raw dataset used for the analysis |
| `Excel_Assignment1_Work_Description.pdf` | One-page work description plus screenshots of results and applied formulas |
| `README.md` | This file |

## Tools Used
Microsoft Excel — SUM, COUNT, AVERAGE, MIN, MAX, IF, SUMIF, COUNTIF, LEFT, MID, RIGHT

## Author
Dhanush — B.Tech, Artificial Intelligence and Data Science, Dhaanish Ahmed College of
Engineering (Anna University)
