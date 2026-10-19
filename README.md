#  Week 1: Data Cleaning with Python & Pandas

##  Project Overview

This project focuses on the fundamentals of data cleaning using **Python and Pandas**. I created a dataset of 80 applications and deliberately introduced data-quality issues to simulate challenges that occur in real-world datasets.

The goal is to explore the data, identify quality issues, and apply appropriate cleaning techniques while preserving the original dataset.

##  Objectives

- Explore a dataset using Pandas.
- Identify and handle missing values.
- Detect and remove exact duplicate records.
- Prepare follow-up lists for applicants with missing contact information.
- Standardize inconsistent date formats.
- Validate the cleaned dataset.

##  Tools & Technologies

- Python
- Pandas
- Google Colab
- GitHub

##  Dataset Description

The dataset contains applicant information, including:

- Applicant Name
- Email
- Phone
- Domain Applied
- University
- Application Date
- Status

Intentional data-quality issues include missing values, duplicate records, inconsistent capitalization, invalid contact details, and inconsistent date formats.

##  Data Cleaning Process

1. **Data exploration:** Examined the dataset's dimensions, column information, missing values, and duplicate records.
2. **Missing values:** Removed records with missing applicant names, filled missing university and application status values, and flagged missing contact details for follow-up.
3. **Duplicate removal:** Removed exact duplicate rows while retaining the first occurrence.
4. **Date conversion:** Converted application dates into a consistent datetime format.
5. **Validation:** Checked the resulting dataset for remaining missing values and other data-quality issues.

##  Project Files

- `Week1_Data_Cleaning_Snethemba_Asande_Mthembu.ipynb` — notebook containing the data generation, exploration, and cleaning process.
- `applicants.csv` — original dataset containing intentional data-quality issues.
- `cleaned_applicants.csv` — dataset after applying the cleaning steps.

*The CSV files will be added to the repository.*

##  Key Learnings

Through this project, I practised using Pandas to investigate data-quality problems, handle missing values, remove duplicates, convert date formats, and maintain separate raw and cleaned datasets.

This project is part of my ongoing Data Science learning journey.

---

**Author:** Snethemba Asande Mthembu  
**Focus:** Data Science | Python | Data Cleaning
