# KARA Child Welfare Database: Minnesota Pilot Analytics & Dashboard System

## Project Overview

This project was completed in collaboration with **Kids At Risk Action (KARA)**, a nonprofit organization focused on improving the lives of abused and neglected children through awareness, research, and policy advocacy.

The goal of the project was to design a unified child welfare reporting system that brings together fragmented Minnesota child welfare data into a structured database and interactive Tableau dashboards.

The original vision was a national child incident database. Due to data availability and quality considerations, the project began as a **Minnesota pilot**, creating a scalable model that can later be expanded to additional states.

## Business Problem

Child welfare data is often scattered across different agencies, public reports, spreadsheets, and dashboards. Data related to child maltreatment, poverty, foster care, juvenile arrests, child deaths, and youth suicide is difficult to compare because each source uses different formats, years, labels, and reporting structures.

This fragmentation creates a major challenge for nonprofit advocates, policymakers, and community leaders. Without a unified system, it becomes difficult to identify risk patterns, understand regional disparities, communicate evidence clearly, and guide policy or funding decisions.

This project addressed that problem by creating a centralized reporting structure that transforms scattered data into accessible, visual, and decision-ready insights.

## Analytical Problem

The main analytical challenge was not only collecting the data, but making it consistent and comparable across counties and years.

The raw data came from many different sources and contained several challenges:

- Inconsistent column names and data formats
- Missing values and incomplete records
- Different year structures across datasets
- County-level and statewide reporting differences
- Sensitive child welfare information requiring careful presentation
- Data spread across Excel files, reports, dashboards, and public portals

To solve this, the project focused on data standardization, relational database design, and dashboard-based storytelling.

## Tools & Technologies

- **Python / Pandas** – preprocessing, data checks, and standardization
- **Excel Power Query** – cleaning, reshaping, and preparing dashboard-ready datasets
- **SQL** – relational database design and data integration
- **Tableau** – dashboard development and visual storytelling
- **PowerPoint / Word** – executive reporting and sponsor presentation

## Data Sources

The project used more than 40 public and nonprofit data sources related to Minnesota child welfare and socioeconomic conditions.

Data themes included:

- Child protection reports
- Socioeconomic indicators
- Poverty and income factors
- Teen births
- Juvenile arrests
- Child mortality
- Youth suicide
- Victim profiles and characteristics
- Maltreatment types
- County-level and year-level trends

## Methodology

### 1. Data Collection

The team gathered child welfare and socioeconomic datasets from public agencies, nonprofit sources, and sponsor-provided references. Minnesota was selected as the pilot state because it had relatively stronger and more consistent data availability.

### 2. Data Cleaning & Standardization

The data was cleaned using Python, Excel, and Power Query. Key cleaning steps included:

- Standardizing column names
- Converting wide-format tables into long-format tables
- Adding county and year identifiers
- Handling missing values
- Aligning categorical labels such as race, gender, maltreatment type, and age group
- Preparing a final dashboard-ready dataset

### 3. SQL Database Design

A relational database structure was designed to connect datasets by county and year.

Core tables included:

- Counties
- Years
- Socioeconomic Data
- Child Protection Reports
- Victim Profiles
- Severe Outcomes
- Juvenile Justice

This structure allowed the project to move beyond scattered files and create a scalable foundation for future state-level or national expansion.

### 4. Tableau Dashboard Development

Five interactive Tableau dashboards were created to help KARA explore and communicate child welfare trends:

1. **Socioeconomic Reporting Overview**
2. **Victim Profiles & Characteristics**
3. **Child Mortality Overview**
4. **Youth Suicide Analysis**
5. **Juvenile Justice Arrests**

The dashboards were designed for both analytical exploration and advocacy storytelling.

## Dashboard Areas

### Socioeconomic Reporting Overview

This dashboard helps users understand how socioeconomic conditions such as poverty, income, and teen births relate to child welfare reporting patterns across Minnesota counties.

### Victim Profiles & Characteristics

This dashboard highlights victim demographics, including age, gender, race or ethnicity, maltreatment type, and relationship to offender. It helps identify potential disparities and vulnerable groups.

### Child Mortality Overview

This dashboard focuses on child mortality trends by county and age group. It supports the identification of high-risk areas and age groups that may require stronger prevention efforts.

### Youth Suicide Analysis

This dashboard examines suicide trends across counties, years, and age groups. It supports discussions around youth mental health and intervention planning.

### Juvenile Justice Arrests

This dashboard analyzes juvenile arrests by county and year, helping stakeholders identify geographic hotspots and overlaps between child welfare and justice system involvement.

## Key Findings

- Socioeconomic stressors such as poverty and teen births appear connected with higher child welfare caseloads.
- American Indian children were disproportionately represented in screened-in investigations.
- Neglect was one of the most common forms of maltreatment found in the data.
- Child mortality and youth suicide trends showed the need for stronger prevention and intervention strategies.
- Juvenile arrest patterns revealed county-level hotspots, especially in larger counties.
- Many severe outcomes occurred without clear prior child protection involvement, highlighting gaps in visibility and prevention.

## Business Impact

This project gave KARA a unified system for communicating child welfare issues with more clarity and credibility.

Instead of relying on scattered spreadsheets and reports, KARA can use the database and dashboards to:

- Present evidence-based insights to policymakers
- Identify county-level risk patterns
- Support advocacy and public awareness
- Strengthen conversations around resource allocation
- Communicate complex child welfare data in a clear visual format
- Build toward a future national child welfare database

## Skills Demonstrated

- Data integration
- Data cleaning and transformation
- SQL database design
- Relational data modeling
- Tableau dashboard development
- KPI reporting
- Public sector analytics
- Social impact analytics
- Executive storytelling
- Sponsor communication
- End-to-end analytics project delivery

## Repository Structure

```text
kara-child-welfare-database/
│
├── README.md
│
├── data/
│   └── Final_cleaned_dashboard_ready.xlsx
│
├── reports/
│   ├── KARA_Final Project Report.docx
│   └── Dashboard explainations.docx
│
├── presentations/
│   └── Team Kara Final Presentation.pptx
│
├── tableau_workbooks/
│   ├── 01_Socioeconomic_Reporting_Overview.twb
│   ├── 02 Victim Profiles & Characteristics.twb
│   ├── 03_Child_Mortality_Overview.twb
│   ├── 04_Youth_Suicide_Analysis.twb
│   └── 05_Juvenile_Justice_Arrests.twb
│
└── images/
    └── dashboard_screenshots/
```

## Project Team

- FNU Sanober
- Uday Kumar Eepu
- Frank Hablawi

## Sponsor

**Kids At Risk Action (KARA)**  
Sponsor contact: Mike Tikkanen

## Academic Context

This project was completed as an analytics capstone project and focused on applying data engineering, visualization, and storytelling to a real nonprofit advocacy challenge.

## Note

This project uses public and aggregated child welfare data. It is intended for academic, advocacy, and analytical demonstration purposes. It should not be interpreted as a real-time government reporting system or as a substitute for official child welfare records.
