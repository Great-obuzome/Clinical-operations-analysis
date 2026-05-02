# ST Meridian Clinical Intelligence
##### Analysis of hospital operations (LOS, readmissions, cost, capacity) using a 2023–2024 clinical dataset, highlighting patient flow inefficiencies.

## Executive summary:

Using Excel, I analyzed a 2023–2024 clinical dataset and built a dashboard to evaluate hospital performance across length of stay, readmissions, cost, and capacity. After identifying that prolonged stays in key departments, high digestive readmissions, and rising ICU costs are the primary drivers of capacity pressure and operational inefficiencies. Based on these findings, the following actions are recommended:

1. Improve discharge planning in high-LOS departments (Neurology, Cardiology)
2. Implement structured post-discharge follow-up for high-risk diagnoses (Digestive)
3. Review ICU resource utilization and patient flow processes
4. Align staffing levels with predictable seasonal demand patterns

## Business Problem:

Efficient patient flow is critical to hospital performance, as it directly impacts capacity, cost, and quality of care. However, hospital leadership observed prolonged patient stays, rising costs in critical units, and recurring capacity pressure despite having access to key metrics such as length of stay, readmissions, and bed occupancy. These metrics were being tracked independently, making it difficult to understand how they interact or where inefficiencies originate. How can we identify the key drivers of prolonged stays, high readmissions, and rising costs, and determine where operational adjustments can improve patient flow and overall hospital efficiency?

## Methodology:

1. Cleaned and transformed multiple clinical tables using Power Query, standardizing key fields across admissions, LOS, readmissions, cost, and capacity.
   
2. Modeled the data in Power Pivot, combining tables into a unified structure for cross-metric analysis.

3. Built an interactive Excel dashboard tracking LOS trends, readmissions by diagnosis, departmental performance, cost distribution, and bed occupancy.
  
4. Conducted exploratory analysis to identify patterns, benchmark performance, and uncover drivers of patient flow inefficiencies.

## Skills:

Excel: Pivot Tables, Advanced Formulas, Data Visualization, Dashboard Design

Power Query: Data Cleaning, Transformation, ETL

Power Pivot: Data Modeling, Relationships, Measures (DAX)

Analysis: Exploratory Data Analysis, Trend Analysis, Performance Benchmarking, Data Storytelling

## Results & Recommendations:

Building this dashboard provided a centralized view of hospital performance across LOS, readmissions, cost, and capacity, enabling a more connected understanding of operational efficiency. By consolidating these metrics, it becomes easier for stakeholders to identify pressure points and monitor performance without relying on fragmented reports.

<img width="1146" height="576" alt="d2" src="https://github.com/user-attachments/assets/214a3588-8df7-4369-b449-9c3cc1489162" /> 
The analysis revealed that prolonged stays in Neurology and Cardiology are key contributors to elevated LOS, while Digestive conditions account for the highest share of readmissions. Additionally, ICU remains the primary cost driver, with emerging cost pressure from the ED, and recurring October admission peaks highlight predictable demand surges. Together, these factors indicate that inefficiencies in patient flow and discharge processes are driving capacity strain and rising operational costs.

Because the most significant operational impact lies in improving patient flow, I recommend the following actions:

1. Improve discharge planning in high-LOS departments (Neurology, Cardiology) to reduce unnecessary patient days
   
2. Implement structured post-discharge follow-up for high-risk diagnoses (Digestive) to lower readmissions
   
3. Review ICU resource utilization and patient flow processes to manage cost concentration
   
4. Align staffing and bed capacity planning with predictable seasonal demand patterns

These interventions would help reduce length of stay, improve bed availability, and control rising costs, while supporting more efficient hospital operations and better patient outcomes.

## Next Steps:

1. Incorporate additional data (patient demographics, treatment details)
   
2. Analyze relationships between LOS, cost, and readmissions
   
3. Build forecasting for admissions and capacity planning
   
4. Automate dashboard updates and refresh process
