# 🏙️ Chicago Community Data Analysis
### 🎓 IBM Data Engineering Specialization – Portfolio Project

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=abdullahahmadd.chicago-community-data-analysis)
![SQL](https://img.shields.io/badge/SQL-blue?logo=postgresql)
![Python](https://img.shields.io/badge/Python-blue?logo=python)
![SQLite](https://img.shields.io/badge/SQLite-blue?logo=sqlite)
![Google Colab](https://img.shields.io/badge/Google%20Colab-orange?logo=googlecolab)

---

## 📑 Table of Contents
1. [Overview](#-overview)
2. [Analytical Objective](#-analytical-objective)
3. [Project Structure](#-project-structure)
4. [Dataset Detail](#-dataset-detail)
5. [Tools & Technologies](#-tools--technologies)
6. [Libraries Used](#-libraries-used)
7. [Skills Demonstrated](#-skills-demonstrated)
8. [Quick Start / Usage](#-quick-start--usage)
9. [Project Workflow](#-project-workflow)
10. [Results](#-results)
11. [Key Findings](#-key-findings)
12. [About This Project](#-about-this-project)

---

## 🧭 Overview
This project focuses on analyzing community-level data for the City of Chicago by integrating socioeconomic indicators, public school performance metrics, and reported crime records. A SQLite relational database is used to perform structured SQL-based analysis and support insight generation.

---

## 🎯 Analytical Objective
- Analyze crime patterns across communities  
- Examine socioeconomic conditions and hardship levels  
- Evaluate school safety and attendance metrics  
- Perform cross-table analysis using SQL joins and views  

---

## 🗂️ Project Structure
| Folder / File | Description |
|---------------|-------------|
| `Data/` | Contains raw CSV datasets used in the analysis |
| `Notebook/` | Google Colab notebook with full SQL and analysis workflow |
| `Results/Key_Analytical_Questions/` | Outputs from core analytical SQL queries |
| `Results/Advanced_SQL_Techniques/` | Results from joins and advanced SQL operations |
| `Results/Visual_Insights/` | Visualizations generated from analyzed data |
| `SQLite/FinalDB.db` | SQLite database containing all loaded tables |
| `README.md` | Project documentation |

---

## 🧾 Dataset Detail
| Dataset | Rows | Description |
|------|------|------------|
| Chicago Census Data | 79 | Community-level socioeconomic indicators |
| Chicago Crime Data | 534 | Reported crime incidents |
| Chicago Public Schools | 567 | School performance and safety metrics |

- **Data Source:** All datasets are sourced from the **City of Chicago Open Data Portal** and provided through IBM Skills Network curated files.

---

## 🛠️ Tools & Technologies
---
- SQL
- Python  
- SQLite  
- Google Colab  

---

## 📚 Libraries Used
- ipython-sql
- sqlite3
- numpy
- pandas   
- matplotlib      

---

## 🧠 Skills Demonstrated
- Relational database design
- Data loading and transformation  
- SQL querying and joins    
- Analytical problem solving  
- Data visualization  
- Insight-driven analysis  

---

## 🚀 Quick Start / Usage
1. Open the notebook in **Google Colab**
2. Upload datasets from the `Data/` folder
3. Run cells sequentially to:
   - Create SQLite database
   - Load tables
   - Execute SQL queries
   - Generate visual insights

---

## 🔄 Project Workflow

1. **Data Collection**  
   Three publicly available datasets related to Chicago communities, schools, and crime were obtained and reviewed to understand their structure, scope, and key attributes.

2. **Environment Setup**  
   A Google Colab notebook was configured with the required Python libraries, and SQLite was selected as the database engine to keep the project self-contained and easy to reproduce.

3. **Data Loading**  
   All CSV files were loaded into pandas DataFrames and then persisted into a SQLite database (`FinalDB.db`) as structured relational tables.

4. **Data Validation**  
   Row counts, column names, and sample records were checked to ensure the data was loaded correctly and relationships between tables were intact.

5. **Analytical SQL Queries**  
   Core analytical questions were answered using SQL, focusing on crime patterns, socioeconomic conditions, and school-related indicators.

6. **Advanced SQL Techniques**  
   Multi-table joins and views were applied to analyze relationships across datasets and demonstrate privacy-aware data access patterns.

7. **Visual Analysis**  
   Key trends and distributions were explored through visualizations to support interpretation and highlight meaningful patterns in the data.

8. **Insight Generation**  
   Results from SQL analysis and visual exploration were consolidated to derive clear, data-driven findings aligned with the project’s analytical objectives.

---

## 📈 Results
This section display the outputs generated during the analysis, organized by analytical queries, advanced SQL techniques, and visual insights.

---

### 🔍 Key Analytical Questions

| 1. Total Crimes Count |
|-----------------------|
| ![Total Crimes](Results/Key%20Analytical%20Questions/total_crimes_count.png) |
| Displays the total number of crime records available in the dataset. |

---

| 2. Low Income Community Areas |
|-------------------------------|
| ![Low Income Communities](Results/Key%20Analytical%20Questions/low_income_community_areas.png) |
| Identifies community areas with per capita income below the defined threshold. |

---

| 3. Crimes Involving Minors |
|----------------------------|
| ![Crimes Involving Minors](Results/Key%20Analytical%20Questions/crimes_involving_minors.png) |
| Lists crime cases where minors were involved based on crime descriptions. |

---

| 4. Kidnapping Crimes Involving Children |
|----------------------------------------|
| ![Child Kidnapping Cases](Results/Key%20Analytical%20Questions/child_kidnapping_cases.png) |
| Highlights kidnapping incidents specifically involving children. |

---

| 5. Crimes Recorded at Schools |
|-------------------------------|
| ![School Crimes](Results/Key%20Analytical%20Questions/crime_types_at_schools.png) |
| Shows distinct crime types that occurred at school locations. |

---

| 6. Average Safety Score by School Type |
|---------------------------------------|
| ![Avg Safety Score](Results/Key%20Analytical%20Questions/average_safety_score_by_school_type.png) |
| Compares average safety scores across elementary, middle, and high schools. |

---

| 7. Top Communities by Poverty Rate |
|-----------------------------------|
| ![Top Poverty Communities](Results/Key%20Analytical%20Questions/top_5_communities_by_poverty.png) |
| Ranks community areas by percentage of households below the poverty line. |

---

| 8. Most Crime-Prone Community |
|------------------------------|
| ![Most Crime Prone Area](Results/Key%20Analytical%20Questions/most_crime_prone_community.png) |
| Identifies the community area with the highest number of reported crimes. |

---

| 9. Highest Hardship Index |
|--------------------------|
| ![Highest Hardship Index](Results/Key%20Analytical%20Questions/highest_hardship_index_community.png) |
| Determines the community area with the highest hardship index. |

---

| 10. Community with Most Crimes |
|-------------------------------|
| ![Community with Most Crimes](Results/Key%20Analytical%20Questions/community_with_most_crimes.png) |
| Maps crime counts to community names to identify the most affected area. |

---

### 🧩 Advanced SQL Techniques

| 1. Join: Schools in High-Hardship Communities |
|-----------------------------------------------|
| ![Schools High Hardship](Results/Advanced%20SQL%20Techniques/school_attendance_high_hardship.png) |
| Uses SQL joins to relate school attendance with community hardship levels. |

---

| 2. Join: Crimes at School Locations |
|-------------------------------------|
| ![Crimes at Schools Join](Results/Advanced%20SQL%20Techniques/crimes_at_school_locations.png) |
| Analyzes crimes occurring at school locations using joined datasets. |

---

| 3. Privacy-Preserving School Ratings View |
|-------------------------------------------|
| ![School Ratings View](Results/Advanced%20SQL%20Techniques/school_ratings_view_all_columns.png) |
| Demonstrates use of SQL views to expose rating icons while hiding raw scores. |

---

| 4. School Name and Leaders Rating |
|----------------------------------|
| ![Leaders Ratings View](Results/Advanced%20SQL%20Techniques/school_leaders_rating_view.png) |
| Displays school names alongside leadership ratings from the created view. |

---

### 📊 Visual Insights

| 1. Crime Distribution by Primary Type |
|---------------------------------------|
| ![Crime by Type](Results/Visual%20Insights/crime_distribution_by_primary_type.png) |
| Shows how reported crimes are distributed across major crime categories. |

---

| 2. Crimes Reported by Year |
|----------------------------|
| ![Crimes by Year](Results/Visual%20Insights/crimes_by_year.png) |
| Visualizes year-wise trends in reported crime incidents. |

---

| 3. Poverty Rate by Community (Top 10) |
|--------------------------------------|
| ![Poverty Top 10](Results/Visual%20Insights/poverty_rate_top_10_communities.png) |
| Highlights communities with the highest household poverty rates. |

---

| 4. Hardship Index Distribution |
|--------------------------------|
| ![Hardship Distribution](Results/Visual%20Insights/hardship_index_distribution.png) |
| Displays the spread of hardship index values across communities. |

---

| 5. Average Safety Score by School Type |
|----------------------------------------|
| ![Safety by School Type](Results/Visual%20Insights/average_safety_score_by_school_type_visual.png) |
| Compares perceived safety across different school categories. |

---

| 6. Poverty vs Per Capita Income |
|--------------------------------|
| ![Poverty vs Income](Results/Visual%20Insights/poverty_vs_per_capita_income.png) |
| Explores the relationship between poverty levels and income. |

---

| 7. Crimes at Schools vs Other Locations |
|----------------------------------------|
| ![School vs Other Crimes](Results/Visual%20Insights/school_vs_non_school_crime_comparison.png) |
| Contrasts crime frequency at schools versus non-school locations. |

---

| 8. Average Student Attendance Distribution |
|--------------------------------------------|
| ![Attendance Distribution](Results/Visual%20Insights/student_attendance_distribution.png) |
| Shows how student attendance rates are distributed across schools. |

---

## 🏁 Key Findings
---

- A total of **533 crime incidents** were recorded in the analyzed dataset, with crime concentration varying significantly across community areas.
- **Riverdale** consistently emerged as a high-risk community, showing the **highest hardship index**, **highest poverty rate**, and multiple schools with comparatively lower attendance.
- **Community Area 25** was identified as the most crime-prone area based on incident frequency.
- Crimes occurring at **school locations** were primarily related to **battery, narcotics, and criminal damage**, indicating safety concerns around educational environments.
- Communities with **higher poverty levels** generally exhibited **lower per capita income**, reinforcing socioeconomic disparities.
- Average school **safety scores were similar across school types** (Elementary, Middle, High), suggesting systemic rather than isolated safety challenges.
- Leadership ratings across schools showed a high prevalence of **“Weak”** classifications, highlighting potential areas for administrative and policy improvement.
- The combined analysis demonstrates a strong relationship between **socioeconomic hardship, crime exposure, and educational conditions**, supporting the need for integrated, data-driven urban planning and policy interventions.

---

## ℹ️ About This Project
---
- This project was developed as part of the **IBM Data Engineering Professional Specialization**.
- It demonstrate practical SQL-based data analysis and database handling using real-world public datasets.
