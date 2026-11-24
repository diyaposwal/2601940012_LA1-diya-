# KNIME Data Preprocessing Workflow — Diya Poswal

**Student:** Diya Poswal  
**Repository:** [2601940012_LA1-diya-](https://github.com/diyaposwal/2601940012_LA1-diya-)

## Assignment Overview

This repository contains the files for a KNIME-based data preprocessing lab assignment. The workflow cleans, transforms, filters, groups, joins, and exports sales data using a visual KNIME workflow.

## Files Included

- `workflow-metadata.xml` — KNIME workflow metadata.
- `workflowset.meta` — Legacy KNIME workflow-set metadata.
- `workflow.svg` — Visual representation of the KNIME workflow.
- `Cleaned_Salees.csv` — Cleaned and processed sales dataset.

## Workflow Description

The KNIME workflow processes sales data through the following sequence:

1. **CSV Reader** — Imports the sales source data.
2. **Duplicate Row Filter** — Removes duplicate records.
3. **Row Filter** — Filters or removes unwanted rows.
4. **Missing Value** — Handles missing values in the data.
5. **String Manipulation** — Cleans or transforms text fields.
6. **Math Formula** — Creates calculated values or transforms numeric fields.
7. **String to Date & Time** — Converts date strings into proper date/time values.
8. **Sorter** — Sorts the dataset by selected columns.
9. **GroupBy** — Aggregates or summarizes records.
10. **Joiner** — Combines related workflow data.
11. **CSV Writer** — Exports the processed output as a CSV file.

## Dataset Information

The cleaned sales file contains fields such as:

- Order ID
- Order Date
- Customer ID
- Customer Name
- Product
- Category
- Quantity
- Unit Price
- Region
- City
- Segment
- Sales

## Purpose

The assignment demonstrates practical use of KNIME for:

- Reading and inspecting CSV data
- Cleaning missing and duplicate values
- Filtering and transforming records
- Creating calculated fields
- Converting data types
- Sorting and grouping results
- Joining datasets
- Exporting cleaned data

## Author

**Diya Poswal**
