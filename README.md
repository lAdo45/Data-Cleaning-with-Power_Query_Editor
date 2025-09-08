# Data-Cleaning-with-Power_Query_Editor

This repository contains hands-on projects showcasing how to clean and transform raw datasets using Power Query Editor in Excel/Power BI. The goal is to prepare messy data into structured, analysis-ready datasets by applying systematic cleaning steps.

📘 Project Overview

Raw data often contains duplicates, null values, inconsistent formats, and unnecessary columns. Using Power Query, these issues can be fixed step by step with applied transformations.

This repository includes multiple datasets (e.g., Movies Dataset, Concert Revenue Dataset) cleaned and transformed with Power Query.

Each project demonstrates a complete ETL (Extract, Transform, Load) workflow.

🔹 Steps to Clean Data in Power Query Editor

1.Load Data into Power Query

Import raw dataset into Excel/Power BI.

Navigate: Data → Get Data → Launch Power Query Editor.

2.Remove Unnecessary Columns

Deleted unused fields like extra IDs or notes.

Helps keep only relevant data for analysis.

3.Rename Columns

Renamed headers into meaningful names (e.g., Year(s).1 → Year).

Improves readability and consistency.

4.Check & Change Data Types

Converted text columns to Date, Number, or Currency where required.

Ensures calculations and visuals work properly.

5.Handle Missing/Null Values

Replaced nulls with default values (like “Unknown”).

Removed empty rows from the dataset.

6.Remove Duplicates

Eliminated duplicate records (e.g., repeated movies or artists).

Ensures clean and unique entries.

7.Trim & Clean Text

Removed extra spaces and formatting issues from columns.

8.Split or Merge Columns

Example: Split Director and Cast into two fields.

Combined fields where necessary.

9.Replace Values

Fixed inconsistent entries (e.g., $229,100,000[b] → $229,100,000).

10.Filter Rows

Removed irrelevant rows such as totals or blanks.

11.Group & Summarize (if needed)

Aggregated values like Total Gross Revenue by Artist.

12.Reorder Columns

Organized columns into logical order for reporting.

13.Load Cleaned Data

Final cleaned dataset loaded back into Excel/Power BI.

📊 Example Projects

📌 Movies Dataset (Cleaned)

Removed duplicates in movie titles.

Renamed and standardized columns (Year, Genre, Rating).

Cleaned text fields like Overview and Director & Cast.

📌 Concert Revenue Dataset (Cleaned)

Standardized revenue values (removed extra characters).

Split columns (e.g., Year, Artist, Tour Title).

Renamed headers and fixed data types (Currency, Year).

🛠️ Tools & Skills Used

Power Query Editor

Data Cleaning & Transformation

Column Profiling & Applied Steps

Data Type Management

ETL Process


📸 Screenshots

👉 Example (Movies Dataset Cleaning):

<img width="1919" height="1022" alt="movies clean dataset" src="https://github.com/user-attachments/assets/b595ee35-7fc9-4ec4-a0e7-8a69e93ceb05" />



👉 Example (Concert Revenue Cleaning):

<img width="1919" height="1022" alt="my_file clean dataset" src="https://github.com/user-attachments/assets/467638f7-ee47-4a63-8028-69810d421fc4" />
