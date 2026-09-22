# Job Market Insights

An end-to-end data analysis project exploring job postings for Data Analyst roles in the United States. The project analyzes in-demand skills, seniority levels, employment types, salary ranges, work-from-home opportunities, and job locations using Python and Power BI.

## Project Overview

The goal of this project is to understand what employers are looking for in Data Analyst roles and identify patterns in job requirements, compensation, employment arrangements, and geographic distribution.

The analysis focuses on the following questions:

- What skills are most frequently requested in Data Analyst job postings?
- How do required skills vary across seniority levels?
- What employment types are most common?
- What salary ranges are represented in the postings?
- How does median salary vary by seniority?
- Which locations have the highest number of postings?
- How many postings explicitly indicate work-from-home opportunities?
- How much salary information is available in the dataset?

## Dataset

The dataset contains **61,953 job postings** retrieved from Google Search results for the search term **"data analyst"** with the search location set to the **United States**.

The dataset includes information such as:

- Job title
- Company
- Location
- Employment/schedule type
- Work-from-home indicator
- Salary information
- Job description
- Extracted skills

> **Note:** The dataset represents U.S. job postings captured through Google Search results and should not be interpreted as a complete representation of the entire U.S. Data Analyst job market.

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**
- **Power BI**
- **Git & GitHub**

## Data Analysis

The analysis involved:

1. Loading and inspecting the raw job-posting dataset.
2. Checking data types, missing values, and duplicate records.
3. Cleaning and standardizing job location values.
4. Extracting and analyzing skills from job descriptions.
5. Categorizing postings into Junior, Senior, Lead, and Other seniority levels based on job titles.
6. Analyzing employment and schedule types.
7. Standardizing and analyzing salary information.
8. Identifying statistically extreme salary observations for salary analysis.
9. Preparing structured job and skill tables for visualization.
10. Building an interactive Power BI dashboard.

## Key Findings

### Job Postings

- **61,953** total job postings
- **10,088** postings contain salary information
- **27,980** postings are explicitly marked as work-from-home

### Most Requested Skills

The most frequently identified skills include:

| Skill | Job Postings |
|---|---:|
| SQL | 31,006 |
| Excel | 19,779 |
| Python | 18,793 |
| Power BI | 17,420 |
| Tableau | 16,823 |
| R | 11,342 |
| SAS | 5,317 |

### Employment Type

Full-time positions represent the largest employment category in the dataset, followed by contractor positions.

### Seniority

The analysis categorizes postings into:

- Junior
- Senior
- Lead
- Other

The "Other" category represents postings where the title did not contain an explicit Junior, Senior, or Lead indicator.

### Salary

Salary information is available for only a subset of postings. The overall median standardized annual salary among postings with salary data is **$88,400**.

Salary analysis also considers statistically extreme observations so that unusually high salary values do not disproportionately affect the analysis.

## Power BI Dashboard

The interactive Power BI dashboard provides:

- Total Job Postings
- Postings with Salary Data
- Work-from-Home Postings
- Median Annual Salary
- Top 10 Skills
- Employment Type Distribution
- Top 10 Job Locations
- Salary Distribution
- Median Salary by Seniority
- Seniority Distribution

Interactive slicers allow the dashboard to be filtered by:

- Seniority
- Employment Type
- Location

  <img width="842" height="717" alt="image" src="https://github.com/user-attachments/assets/016a4d5d-8b62-4629-93ee-83938a9f454d" />

