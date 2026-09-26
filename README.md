# Employee Performance Dashboard

##  Project Overview

**Employee Performance Dashboard** is an interactive data analytics project developed using **Microsoft Excel** to clean, transform, analyze, and visualize employee-related data.

The project focuses on transforming a raw employee dataset into a structured and interactive dashboard that provides insights into **employee performance, demographics, salary, experience, and other workforce characteristics**.

The dataset was first cleaned and prepared to ensure consistency and reliability. Additional derived fields were then created to categorize employees into meaningful groups such as **Age Group, Position Level, and Salary Range**.

The prepared data was analyzed using **Pivot Tables** and presented through an interactive Excel dashboard using **charts and slicers**. This allows users to filter the data and explore employee performance from different perspectives.

---

##  Project Objectives

The main objectives of this project were to:

* Clean and prepare raw employee data for analysis.
* Filter the dataset to include relevant active employees.
* Remove inconsistent or unwanted records.
* Create meaningful derived categories for analysis.
* Analyze employee performance across different demographic groups.
* Explore relationships between salary, experience, and performance.
* Create Pivot Tables to summarize important employee metrics.
* Develop an interactive Excel dashboard.
* Allow users to explore employee data using slicers and visualizations.

---

##  Data Cleaning & Preparation

Before creating the dashboard, the raw dataset was cleaned and transformed to improve its consistency and usability.

### 1. Filtered Active Employees

The dataset was filtered to include only **active employees**.

This ensures that the dashboard focuses on employees who are currently part of the organization.

### 2. Removed Unwanted Records

Records where the gender value was **"Other"** were removed as part of the dataset preparation process to maintain consistency with the selected analysis categories.

### 3. Removed Duplicate Records

Duplicate records were identified and removed to prevent the same employee information from being counted multiple times during analysis.

### 4. Created Derived Columns

Additional columns were created to make the dataset easier to analyze.

#### Age Group

Employees were categorized into age groups based on their age.

This allows employee performance and workforce distribution to be compared across different age categories.

#### Position Level

Employees were grouped according to their level of experience or position.

This provides a structured way to compare performance across different experience levels.

#### Salary Range

Employees were categorized into salary brackets.

This allows salary distributions and relationships with other employee characteristics to be explored more easily.

### 5. Data Formatting

The dataset was reviewed to ensure that:

* Numerical fields were stored correctly.
* Categorical fields were consistently formatted.
* Dates were formatted appropriately.
* Duplicate records were removed.
* Required fields were available for analysis.

---

##  Data Analysis Workflow

The project followed the following workflow:

```text
Raw Employee Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Filter Active Employees
        │
        ▼
Remove Duplicates & Inconsistent Records
        │
        ▼
Create Derived Columns
        │
        ├── Age Group
        ├── Position Level
        └── Salary Range
        │
        ▼
Pivot Tables
        │
        ▼
Pivot Charts
        │
        ▼
Interactive Slicers
        │
        ▼
Employee Performance Dashboard
```

---

##  Analysis & Dashboard

After completing the data preparation stage, Pivot Tables were created on a separate worksheet to summarize the main metrics.

The summarized information was then used to create the interactive dashboard.

### 1. Employee Performance

The dashboard provides an overview of employee performance and allows performance-related information to be explored across different employee categories.

### 2. Gender Distribution

The dashboard visualizes the distribution of employees by gender.

This provides a basic demographic overview of the workforce represented in the dataset.

### 3. Age Group Analysis

Employees are grouped into different age categories to allow comparison of workforce distribution and performance across age groups.

### 4. Salary Analysis

Salary information is analyzed using the created salary categories.

This makes it easier to examine salary distributions and compare them with other employee characteristics.

### 5. Experience & Position Analysis

The Position Level field allows employees to be grouped based on experience or position.

This provides an additional dimension for exploring differences in employee performance.

### 6. Interactive Filtering

Excel slicers allow users to filter the dashboard according to selected categories.

Users can interact with the dashboard to explore specific groups without manually filtering the underlying dataset.

---

##  Dashboard Features

The dashboard includes:

*  Employee performance analysis
*  Gender distribution
*  Age group analysis
*  Salary range analysis
*  Experience and position comparisons
*  Interactive slicers
*  Pivot Table-based analysis
*  Interactive charts

---

##  Tools & Technologies

| Tool / Technology   | Purpose                                            |
| ------------------- | -------------------------------------------------- |
| **Microsoft Excel** | Data cleaning, analysis, and dashboard development |
| **Pivot Tables**    | Data summarization and analysis                    |
| **Pivot Charts**    | Visualization of employee metrics                  |
| **Slicers**         | Interactive filtering                              |
| **Excel Formulas**  | Data transformation and derived fields             |

---

##  Key Variables

The dashboard analyzes employee information across several dimensions.

| Category          | Examples             |
| ----------------- | -------------------- |
| Employment Status | Active employees     |
| Demographics      | Gender, Age Group    |
| Experience        | Position Level       |
| Compensation      | Salary, Salary Range |
| Performance       | Employee Performance |
| Filtering         | Dashboard Slicers    |

---

##  Analysis Questions

The dashboard can be used to explore questions such as:

* How is employee performance distributed across the organization?
* How is the workforce distributed across different age groups?
* What is the gender distribution of active employees?
* How are employees distributed across salary ranges?
* How does employee performance vary across different position levels?
* How can salary and experience categories be compared?
* What patterns can be observed when different dashboard filters are applied?

---

##  Project Purpose

The main purpose of this project is to demonstrate how a raw employee dataset can be transformed into an **interactive analytical dashboard using Microsoft Excel**.

The project covers the complete workflow from:

**Data Cleaning → Data Transformation → Data Analysis → Visualization → Interactive Dashboard**

This provides a practical example of using Excel as a tool for exploratory data analysis and business intelligence.

---

##  Skills Demonstrated

Through this project, I gained practical experience in:

* Data cleaning
* Data transformation
* Data validation
* Excel formulas
* Derived variable creation
* Pivot Tables
* Pivot Charts
* Interactive Slicers
* Dashboard development
* Demographic analysis
* Employee performance analysis
* Salary analysis
* Data visualization
* Business intelligence
* Exploratory data analysis

---

##  Project Structure

```text
Employee_Performance_Dashboard/
│
├── Employee Performance Dashboard.xlsx
│
└── README.md
```

> **Note:** Update the Excel filename above if the actual filename in your repository is different.

---

##  Project Outcome

The final outcome of the project is an **interactive Employee Performance Dashboard** that transforms cleaned employee data into an easy-to-explore visual interface.

The dashboard combines Pivot Tables, charts, and slicers to allow users to examine employee performance and workforce characteristics from multiple perspectives.

---
