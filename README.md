Of course. Here is the project README, concisely written within 40 lines.

***

# Power BI Healthcare Analytics Dashboard

## Project Overview
This project transforms raw healthcare data into an interactive Power BI dashboard. It analyses key metrics like billing amounts, treatment costs, and patient demographics to support data-driven decision-making for healthcare providers.

## Key Features
*   **Data Modelling**: Cleaned data from multiple CSVs and established a robust model with auto-detected relationships.
*   **Custom Date Table**: Built a DAX-based date table using `CALENDARAUTO` for advanced time intelligence analysis.
*   **DAX Calculations**: Developed various measures, including `SUMX` for row-level calculations like total room charges and `DATEDIFF` for patient length of stay.
*   **Interactive Visuals**: Utilised Azure Maps for geographical analysis and clustered charts to compare departmental performance.
*   **Dynamic UX**: Implemented field parameters to switch map views between city and state, a theme switcher for light/dark modes, and a collapsible slicer panel using bookmarks.

## Dashboard Pages
The report features two identical pages with different themes:
1.  **Main Dashboard (Light Mode)**: The primary view with a professionally designed light background.
2.  **Main Dashboard (Dark Mode)**: An alternative dark-themed version for user preference.

## Key Insights
*   **Financial Performance**: Offers a clear view of total billing, breaking it down into treatment costs, medication, and room charges, while also showing out-of-pocket expenses.
*   **Procedural Analysis**: Identifies high-revenue procedures like X-rays by showing both the total billing amount and the percentage of the grand total.
*   **Geographical Trends**: The Azure Map highlights high-revenue cities and states, enabling targeted operational focus.
*   **Departmental Efficiency**: Compares departmental billing amounts to pinpoint top-performing areas within the hospital.

## Project Conclusion
This project successfully demonstrates the creation of a comprehensive and user-friendly analytics tool. By leveraging advanced Power BI features, the dashboard delivers actionable insights to help optimise financial performance and operational efficiency in a healthcare setting.
