# 🏏 T20 World Cup 2022 Cricket Analytics Dashboard - Power BI

🔗 **[👉 Click here to view and interact with the Live Dashboard](https://app.powerbi.com/groups/me/reports/aa0a17b9-e307-413c-8048-5b5be5c2880c/ReportSectionddd36287ad29b36004c1?experience=power-bi)**  
Use filters to explore different roles, teams, and stages. You can also combine players to build your **Final XI** and instantly see performance metrics update.

---

## 📌 Overview

This project is an **interactive analytical dashboard** built in **Power BI**, focused on analyzing the **ICC Men’s T20 World Cup 2022** player performances. The insights aim to assist selectors, coaches, analysts, and fans in forming the optimal playing XI by analyzing various player roles: **Power Hitters, Anchors, Finishers, All-rounders, and Fast Bowlers**.

---

## 💼 Business Problem

Cricket teams rely heavily on data to make informed decisions. However, raw statistics scattered across multiple sources can make it challenging to identify consistent performers or strategic combinations. There’s a need to centralize, clean, and visualize this data effectively to:
- Compare player performance based on roles.
- Build a custom best-playing XI.
- Aid coaching decisions using performance trends.

---

## 🎯 Objective

- Scrape and consolidate T20 World Cup 2022 stats.
- Transform and model data to make it analyzable.
- Provide interactive visualizations to identify standout players by role.
- Enable users to create a **Final XI** using measurable metrics.

---

## 🧰 Tech Stack & Process

### 🔎 1. Web Scraping
- **Source**: [ESPN Cricinfo – T20 WC Match Results](https://www.espncricinfo.com/records/tournament/team-match-results/icc-men-s-t20-world-cup-2022-23-14450)
- **Tools**: Power BI Web Connector or Python (BeautifulSoup, pandas)
- **Data Extracted**: Player stats, teams, scores, roles, match dates

### 🧹 2. Data Cleaning
- Removed null/duplicate rows
- Standardized player/team names
- Normalized inconsistent date and numeric formats
- Classified player roles: Openers, Finishers, Bowlers, All-Rounders, etc.

### 🔁 3. Data Transformation & Modeling
- Power Query Editor for merging and transforming datasets
- Created new calculated columns (Strike Rate, Economy Rate, Boundaries %)
- Modeled data in a star schema for optimized performance

### 📊 4. Power BI Dashboard Features

#### Key Dashboard Tabs
- Role-based player analysis (Power Hitters, Anchors, Finishers, All-Rounders, Fast Bowlers)
- Stage-based filters: Qualifier & Super 12
- "Select Final XI" filter with live stat aggregation

#### Visuals
- KPI Cards: Total Runs, Average, Strike Rate
- Bar Charts: Top scorers and wicket-takers by category
- Bubble Charts: Avg vs SR, Economy vs Avg
- Player performance tables with conditional formatting

---

## 🧠 Key Insights

- **Virat Kohli** had the highest average (98.67) with consistent performance.
- **Suryakumar Yadav** had the highest strike rate (189.68) among top scorers.
- **Rilee Rossouw** combined explosive hitting with reliability (SR 169.88, Avg 35.25).
- All-Rounders like **Hardik Pandya** and **Glenn Maxwell** provided depth across departments.
- The dashboard's **Final XI selection** tool enables comparative decision-making with instant KPI summaries.

---

## 📈 Business Impact

- Delivered a **data-backed player evaluation tool** for T20 tournament analysis.
- Empowered strategic **team selection** based on quantifiable role performance.
- Enhanced fan engagement through dynamic, role-based cricket insights.
- Demonstrated how **data science bridges sports analysis and visualization**.

---

## 🧠 Learnings

- Built full-stack BI workflow from web scraping to dashboard delivery
- Learned advanced Power Query transformation techniques
- Applied DAX for complex metric calculations
- Gained practical experience in storytelling with real-world sports data

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Allow data source connection for web-based updates (if applicable)
3. Interact with filters and tabs to explore players by role, performance, and stage
4. Use the “Select Final XI” feature to create your dream team

---

## 🧰 Tools & Technologies Used

| Tool            | Purpose                               |
|------------------|----------------------------------------|
| Power BI         | Visualization & dashboard creation     |
| Power Query      | Data cleaning & transformation         |
| DAX              | Measure creation & advanced metrics    |
| ESPN Cricinfo    | Data source (web scraped)              |

---

## 📎 Credits

- **Data Source**: [ESPN Cricinfo](https://www.espncricinfo.com/)
- **Dashboard & Analysis**: [Your Name]
- **Icons & Design**: Power BI native visuals

---

## 📫 Contact

Feel free to connect or ask questions:

📧 Email: ruhiroza10@gmail.com  
💼 LinkedIn: [linkedin.com/in/Ruhi]([https://linkedin.com/in/yourname](https://www.linkedin.com/in/ruhisharma14/))

---
