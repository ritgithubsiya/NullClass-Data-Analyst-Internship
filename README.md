# NullClass Data Analyst Internship – Tableau Projects

**Pragati**  
NullClass Data Analyst Internship Tasks  
January 2026

This repository contains all 6 Tableau visualization tasks completed during the NullClass internship.  
Each task is organized in its own folder with:

- A detailed specific folders for each task explaining the objective, every filter/condition applied, calculated fields used, and result notes.
- Screenshots of the final chart(s) (uploaded directly to the root with clear names like `task1-bar-chart.png`).

## Project Structure
- **Task-1-Intern-Bar-Chart**  
- **Task-2-Scatter-Plot**  
- **Task-3-Tree-Map**  
- **Task-4-Qualification-Drilldown-Map**  
- **Task-5-Stacked-Bar**  
- **Task-6-Box-Plot**  

All task descriptions are inside each folder's.  
Screenshots are in the root folder with names like:
- `task1-bar-chart.png`
- `task2-scatter-plot.png`
- `task3-tree-map-sheet.png` and `task3-tree-map-dashboard.png`
- `task4a-africa-job-map.png`
- `task4b-drilldown-location-map.png`
- `task4-map-with-click-dashboard.png`
- `task5-stacked-bar.png`
- `task6-box-plot.png`

## Special Notes on Tasks 3 and 4

**Task 3 – Top 10 Companies (Tree Map)**  
- Two images uploaded:  
  - `task3-tree-map-sheet.png`: Main tree map sheet (shows single large rectangle for DTE Energy due to strict filters).  
  - `task3-tree-map-dashboard.png`: Dashboard view with floating messages.  
- Reason for dashboard: Several filters (Latitude < 10, B.Tech qualification, LinkedIn portal, Company Size ≥ 10,000) caused the tree map to become blank when applied together.  
  I created a dashboard where users can turn sensitive filters on/off and see helpful floating messages like “NO DATA AVAILABLE CHECK FILTER”.

**Task 4 – Qualification Drilldown Map (Map with Click)**  
- Three images uploaded:  
  - `task4a-africa-job-map.png`: Main map sheet showing orange dots in Africa.  
  - `task4b-drilldown-location-map.png`: Drilldown sheet (detailed view when clicking a dot).  
  - `task4-map-with-click-dashboard.png`: Full dashboard combining both sheets with click-to-filter action.  
- Interactive feature: Clicking any dot on the main map (Task4a) filters and shows more precise location details in the second map (Task4b).

## Technologies Used
- Tableau Desktop / Public
- Calculated fields (REGEXP_EXTRACT for salary, LEN/CONTAINS for strings, MOD for even/odd, DATEPART for time)
- Filters (quick, range, wildcard, calculated boolean)
- Dashboard actions (filter on click)
- Tree maps, box plots, stacked bars, scatter plots, geographic maps

All tasks were completed with strict conditions from NullClass, including time-based visibility (3–5 PM IST or 3–6 PM IST for Task 4).

Feel free to explore each task folder for full step-by-step explanations and screenshots.

Thank you for viewing my internship Tasks!
