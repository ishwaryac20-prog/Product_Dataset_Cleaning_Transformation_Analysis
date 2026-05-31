# Product Dataset – Data Cleaning & Transformation Using Excel

## Project Overview
This project focuses on cleaning and preparing a product dataset using Microsoft Excel. The dataset contained duplicate records, missing values, inconsistent text formats, category errors, and formatting issues that required correction before analysis.

The objective was to apply Excel data-cleaning techniques to improve data quality, consistency, and usability.

---

## Tools Used
- Microsoft Excel
- Excel Functions:
  - COUNTBLANK
  - AVERAGE
  - PROPER
  - TRIM
  - CLEAN
  - CONCATENATE / CONCAT

---

## Tasks Performed

### 1. Removing Duplicates
- Identified duplicate records using the Product ID column.
- Used **Data → Remove Duplicates**.
- Removed 3 duplicate records.

### 2. Handling Missing Values
#### Price Column
- Identified blank cells using COUNTBLANK.
- Replaced missing values with the average price.

#### Category Column
- Found blank category values.
- Replaced missing entries with "Unknown".

### 3. Correcting Inconsistent Data
#### Product Name
- Standardized text using:
  - PROPER()
  - TRIM()
  - CLEAN()

#### Category Column
- Identified misspelled category names such as "Electroni".
- Corrected them using Find & Replace.
- Replaced all incorrect values with "Electronics".

### 4. Splitting and Merging Data
#### Product ID Split
Separated Product ID into:
- Manufacturing Date
- Country Code

Using **Text to Columns**.

#### Product Brand Creation
Merged:
- Brand Name
- Product Name

Into a new column called **Product Brand**.

### 5. Number Formatting
- Converted Price column into Currency format.
- Formatted Manufacturing Date as DD-MM-YYYY.

### 6. Conditional Formatting
- Applied Data Bars to the Price column.
- Highlighted records containing "Electronics" in the Category column.

---

## Key Learnings
- Data Cleaning Techniques
- Handling Missing Values
- Removing Duplicates
- Text Standardization
- Data Formatting
- Conditional Formatting
- Data Preparation for Analysis

---

## Project Outcome
The dataset was successfully cleaned and transformed by removing duplicates, handling missing values, correcting inconsistencies, restructuring columns, and applying formatting techniques. The final dataset is accurate, consistent, and ready for analysis and reporting.

---

## Author
**Hema Ishwarya**  
AI-Driven Data Analytics  
ENTRI
