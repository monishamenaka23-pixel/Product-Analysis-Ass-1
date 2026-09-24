Project Overview
This project was completed as part of my Data Analytics learning journey, focusing on Microsoft Excel for Data Exploration and Analysis.
The objective of this assignment was to perform basic data analysis, logical categorization, conditional aggregation, and text manipulation using Excel formulas and functions. This project demonstrates foundational spreadsheet skills that are essential for data cleaning, exploration, and reporting.
As an aspiring Data Analyst, I am building this repository to showcase my practical Excel skills and portfolio projects.
## 📁 Dataset Information
The dataset contains product-related data with the following attributes:
- Product ID
- Product Name
- Brand Name
- Price ($)
- Quantity
- Category
### Sample Categories
- Electronics
- Fashion
- Kitchen
- Outdoor
- Accessories
## 🎯 Objectives
The assignment focuses on:
- Data Exploration
- Data Summarization
- Logical Analysis
- Conditional Aggregation
- Text Manipulation
- Excel Formula Application
## ✅ Tasks Performed
### 1. Basic Data Exploration
Using Excel functions:
- **SUM()** → Calculated total price of all products
- **COUNT()** → Counted the number of products
- **AVERAGE()** → Calculated average product price
#### Formulas Used excel
=SUM(D2:D35)
=COUNT(D2:D35)
=AVERAGE(D2:D35)
### 2. Minimum and Maximum Price Analysis
Using statistical functions:
MIN()** → Lowest product price
MAX()** → Highest product price
#### Formulas Used excel
=MIN(D2:D35)
=MAX(D2:D35)

### 3. Price Classification Using IF Function
Created a new column named **Price Range**.
#### Business Logic
- Price ≥ 500 → High Price
- Price < 500 → Standard Price
#### Formula Used excel
=IF(D2>=500,"High Price","Standard Price")
### 4. Conditional Aggregation
### SUMIF Function
Calculated total price of products in the **Electronics** category.
=SUMIF(F2:F35,"Electronics",D2:D35)
#### COUNTIF Function
Counted products with price less than $100.
=COUNTIF(D2:D35,"<100")
### 5. Text Manipulation Functions
Extracted information from the **Product ID** field.
Example Product ID: text
28-JAN-US
#### Day Extraction
Using **LEFT()**
=LEFT(A2,2)
Output:
28
#### Month Extraction
Using **MID()**
=MID(A2,4,3)
Output:
JAN
#### Country Code Extraction
Using **RIGHT()**
=RIGHT(A2,2)
Output:
US
## 📈 Key Excel Functions Used
| Category | Functions |
| Data Summarization | SUM, COUNT, AVERAGE |
| Statistical Analysis | MIN, MAX |
| Logical Analysis | IF |
| Conditional Aggregation | SUMIF, COUNTIF |
| Text Manipulation | LEFT, MID, RIGHT |
## 🛠 Tools Used
- Microsoft Excel
- Excel Formulas and Functions
- GitHub
