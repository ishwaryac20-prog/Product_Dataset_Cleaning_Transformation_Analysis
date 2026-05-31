# Product Dataset – Data Cleaning and Transformation Using Excel

## Project Description

This project focuses on cleaning and transforming a product dataset using Microsoft Excel. The dataset contained duplicate records, missing values, inconsistent text formatting, category errors, and formatting issues that needed to be resolved before analysis.

The main objective of this project was to apply data cleaning and preprocessing techniques to improve data quality, consistency, and usability. The cleaned dataset can be used for accurate reporting and business analysis.

---

## Project Objectives

- Remove duplicate records from the dataset
- Identify and handle missing values
- Correct inconsistent text formats
- Fix spelling errors in category names
- Split and merge columns where required
- Apply number and date formatting
- Use conditional formatting for better data visualization
- Prepare the dataset for further analysis

---

## Dataset Fields

The dataset contains the following columns:

- Product ID
- Product Name
- Brand Name
- Price
- Quantity
- Category

---

## Tasks Performed

### 1. Removing Duplicates

Duplicate records were identified using the Product ID column.

**Steps Performed:**
- Selected the Product ID column.
- Used Data → Remove Duplicates.
- Expanded the selection to include all columns.
- Removed duplicate records.

**Result:**
- 3 duplicate records were removed successfully.

---

### 2. Handling Missing Values

#### Price Column

- Used COUNTBLANK() to identify missing values.
- Found 3 blank cells.
- Replaced missing prices with the average value of the Price column.

#### Category Column

- Identified blank category values.
- Replaced missing values with "Unknown".

**Result:**
- All missing values were handled successfully.

---

### 3. Correcting Inconsistent Data

#### Product Name Standardization

The Product Name column contained inconsistent text formatting.

**Functions Used:**
- PROPER()
- TRIM()
- CLEAN()

These functions were used to standardize capitalization and remove unwanted spaces and characters.

#### Category Correction

The Category column contained misspelled values such as:

- Electroni

Using Find & Replace, all incorrect values were replaced with:

- Electronics

**Result:**
- 5 category spelling errors were corrected.

---

### 4. Splitting and Merging Data

#### Splitting Product ID

The Product ID column was split into:

- Manufacturing Date
- Country Code

**Method Used:**
- Text to Columns

#### Merging Columns

Brand Name and Product Name were merged into a new column called:

- Product Brand

**Function Used:**
- CONCAT()

---

### 5. Number Formatting

#### Price Column

Applied currency formatting using:

- CTRL + SHIFT + 4

#### Manufacturing Date

Formatted dates using:

- DD-MM-YYYY format

---

### 6. Conditional Formatting

#### Price Column

Applied:

- Data Bars (Gradient Fill)

to visually represent price values.

#### Category Column

Applied:

- Highlight Cells Rules
- Text That Contains

to highlight all records containing:

- Electronics

---

## Excel Features Used

- Remove Duplicates
- Find and Replace
- Text to Columns
- Conditional Formatting
- Currency Formatting
- Date Formatting

---

## Excel Functions Used

```excel
COUNTBLANK()
AVERAGE()
PROPER()
TRIM()
CLEAN()
CONCAT()
IF(ISBLANK())
```

---

## Project Outcome

After completing the data cleaning and transformation process:

- Duplicate records were removed.
- Missing values were handled.
- Inconsistent text formats were corrected.
- Category spelling errors were fixed.
- Product ID was successfully split into meaningful fields.
- Brand and Product names were merged.
- Proper number and date formatting were applied.
- Conditional formatting improved data visualization.

The final dataset is clean, structured, consistent, and ready for analysis.

---

## Conclusion

This project demonstrates the practical application of Excel data cleaning and transformation techniques. By resolving data quality issues and improving dataset structure, the final dataset became more accurate, reliable, and suitable for business analysis and reporting.

---

## Author

**Hema Ishwarya**

**Course:** AI-Driven Data Analytics

**Institute:** ENTRI
