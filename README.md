# Project-Management-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/65c2d649-1445-437d-9596-cdec56b0f7a8/9263f5c105491c5b0c0a?experience=power-bi

## Problem Statement

Many organizations struggle to effectively track and visualize key metrics across multiple projects, leading to challenges in decision-making and resource allocation. This project management dashboard addresses the need for a comprehensive, data-driven solution to monitor project performance, financial impact, and progress across different regions and project types.

The dashboard aims to solve the following problems:

1. Lack of visibility into project benefits and costs across regions
2. Difficulty in tracking project completion percentages by phase
3. Inability to quickly assess project status and type distribution
4. Challenges in comparing project benefits and costs over time
5. Limited insight into the financial impact of different project types (Cost Reduction, Income Generation, Process Improvement, Working Capital Improvement)

By providing a centralized, visual representation of key project metrics, this Power BI dashboard enables stakeholders to make informed decisions, optimize resource allocation, and improve overall project performance across the organization.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is in PDF format.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Select "column profiling based on entire dataset" to ensure comprehensive data analysis.
- Step 4 : It was observed that in none of the columns errors & empty values were present, ensuring data quality across all fields.
- Step 5 : For calculating total project benefits and costs, sum aggregations were used across regions and project types.
- Step 6 : In the report view, under the view tab, an appropriate theme was selected to enhance visual appeal.
- Step 7 : Created visualizations for Sum of Project Benefit and Cost by Region using bar charts.
- Step 8 : Visualized Sum of Completion% by Phase using a horizontal bar chart.
- Step 9 : Added a table showing Project Name, Type, Status, Cost, and Benefit for detailed project information.
- Step 10 : Created a line chart to show Sum of Project Benefit and Cost by Year for trend analysis.
- Step 11 : Implemented filters for Project Type and Project Name to allow for interactive data exploration.
- Step 12 : Created calculated columns or measures in DAX for total project benefits, costs, and completion percentages.
- Step 13 : The report was then published to Power BI Service.



# Insights

1. Regional Distribution: The North region accounts for the highest proportion of both project benefits (34.43%) and costs (34.4%), followed by the West, South, and East regions.

2. Project Phases: The dashboard reveals varying completion percentages across different project phases, allowing for easy identification of bottlenecks or delays.

3. Project Types: The dashboard categorizes projects into Cost Reduction, Income Generation, Process Improvement, and Working Capital Improvement, providing insights into the focus areas of the organization.

4. Financial Impact: By visualizing project benefits and costs over time, the dashboard helps identify trends and forecast future financial impacts.

5. Project Status: The ability to filter by project status (In-Progress, Cancelled, On-Hold) enables quick assessment of the overall project portfolio health.

6. Resource Allocation: By comparing project costs and benefits, stakeholders can make data-driven decisions on resource allocation and project prioritization.

7. Performance Metrics: The dashboard allows for easy identification of high-performing projects and areas needing improvement, facilitating strategic decision-making.
