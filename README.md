# Product Data Exploration and Analysis Using Microsoft Excel

## Description

This project uses Microsoft Excel to perform an in-depth exploration of product data. Through calculations, logical operations, conditional analysis, and data formatting,text formatting are employed to clean, process, and interpret the dataset.
This project applies Microsoft Excel to conduct exploratory data analysis on a 34-product portfolio as part of the Program in AI Driven Data Analytics. The analysis employs a combination of statistical functions (SUM, AVERAGE, MIN, MAX, COUNT), logical operations (IF), conditional aggregations (SUMIF, COUNTIF), and text manipulation (LEFT, RIGHT, MID) to transform raw product data into business intelligence.

---

# Getting Started

## Dependencies



- *Microsoft Excel*: Version 2016 or later, or Microsoft 365. All analysis was performed using standard Excel functions.
- *Operating System*: Windows or Excel Online. No OS-specific features were used.
- *Technical Skills*: Basic familiarity with Excel formulas and cell referencing to review and modify calculations.

---

# Installing

1. *Get the file*: Click the green <> Code button at the top of this repository → Select Download. 
   - Alternative: Download Product_Analysis.xlsx directly from the file list above.
2. *Extract*: If you downloaded the file, right-click the file → Extract All... to a folder on your computer.
3. *Open*: Launch Microsoft Excel → File → Open → Navigate to Product_Analysis.xlsx.
4. *Enable content*: If Excel shows a yellow "Protected View" banner, click Enable Editing to view formulas and interact with calculations.
5. *Verify*: All data and formulas are self-contained. 

---

# Executing Program

## Steps to Run the Project

1. *Open the Workbook*: Launch Product_Analysis.xlsx in Microsoft Excel. Click Enable Editing if prompted by Protected View.
2. *Review Raw Data*: Navigate to the Dataset sheet to examine the 34-product portfolio with fields for Product ID, Name, Brand, Price, Quantity, and Category.
3. *Inspect Key Metrics*: Scroll to the Basic Data Exploration section to view calculated results:
## Example Formulas Used

### SUM Formula

```excel
=SUM(D2:D35)
```

### AVERAGE Formula

```excel
=AVERAGE(D2:D35)
```

### COUNTA Formula

```excel
=COUNTA(B2:B35)
```

### MAX Formula

```excel
=MAX(D2:D35)
```

### MIN Formula

```excel
=MIN(D1:D34)
```

---

## Help

### Troubleshooting Common Issues

#### 1. Excel file not opening or shows "Protected View" warning
*Cause*: Files downloaded from GitHub open in Protected View by default for security.  
*Fix*: Click Enable Editing in the yellow banner at the top of Excel. If the file still won't open, confirm Microsoft Excel 2016, Microsoft 365, or Excel Online is installed.

#### 2. Formulas return #NAME?, #VALUE!, or #DIV/0! errors
*Cause*: Cell references don't match your sheet layout, or syntax is incorrect.  
*Fix*: 
- Ensure every formula starts with =
- Verify ranges: (D2:D35) should point to your Price column and F2:F35 to Category
- For SUMIF/COUNTIF, use straight quotes: "Electronics" not “Electronics”
- Press Ctrl + ~ to view all formulas and check for typos
- If you see #DIV/0!, check that Price and Quantity columns contain numeric values, not text

# Authors

**Priyadharshini Naresh D**  
B.com International Accounting 

---

## Version History

### v1.0 - Final Submission 
- *Initial Release*: Completed exploratory data analysis for Program in AI Driven Data Analytics
- *Dataset*: Integrated 34-product portfolio with Product ID, Name, Brand, Price, Quantity, Category
- *Analysis*: Implemented statistical functions SUM, AVERAGE, MIN, MAX, COUNT for portfolio metrics
- *Business Logic*: Applied conditional aggregation using SUMIF, COUNTIF and logical IF statements
- *Data Wrangling*: Parsed composite Product IDs using LEFT, MID, RIGHT text functions
- *Key Findings*: Identified $10,100 total portfolio value with Electronics representing 79.7% or $8,050

---

## License

This project is submitted as part of the *Program in AI Driven Data Analytics* curriculum. 

All content is for educational and academic evaluation purposes. Redistribution or commercial use without permission is not permitted.

---

## Acknowledgments

- *Microsoft Excel*: Primary analytical platform used for all data processing and calculations
- *Course Faculty*: Program in AI Driven Data Analytics, for project guidance and evaluation framework
- *Dataset Source*: Simulated product data created for academic analysis exercises


