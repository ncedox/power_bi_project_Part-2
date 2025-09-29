# Power BI Project – Part 2
This project builds on the analysis of water sources and community data in Maji Ndogo. 
The focus was on creating a strong data model, cleaning the datasets, and developing interactive dashboards in Power BI to support decision-making at both national and provincial levels.
## Skills Highlighted
Data cleaning and transformation in Power Query.<br>
Data modeling with fact and dimension tables.<br>
Managing many-to-many relationships using bridging tables.<br>
Designing star and multi-star schemas.<br>
Creating calculated columns for time-based analysis.<br>
Building interactive dashboards with maps, charts, and filters.<br>
Troubleshooting and adjusting relationship directionality
# Dashboards
## National Page
Map of provinces. <br>
Treemap: people served by source type. <br>
Column charts: water sources per town, and source counts by type. <br>
Filters across national, provincial, rural, and town levels
<img width="1326" height="727" alt="image" src="https://github.com/user-attachments/assets/a24291bf-6c9f-4bdc-975d-87e7426e0ec8" />

## Queues Page
Line chart: average queue time per hour. <br>
Bar chart: average queue time per day. <br>
Queue composition breakdown. <br>
Total time queued per province, <br>
All visuals filtered to shared taps only. <br>
Added a Day Name column for time-based insights. <br>
Interactive filtering showed patterns such as:
Men dominate queues in Amanzi, but nationally queues are mostly women
Mondays: 71% women in queues; Saturdays: 40% men
<img width="1282" height="736" alt="image" src="https://github.com/user-attachments/assets/488717bc-5ab7-405c-935f-2c4d484fb01c" />

## Pollution Page
Composition chart by contamination type.  <br>
Insights at provincial level, e.g.:,  <br>
Many provinces have few clean wells (green = bad in this case).  <br>
Akatsi has many clean wells but most polluted wells are chemically contaminated
<img width="1276" height="726" alt="image" src="https://github.com/user-attachments/assets/55e510d5-b5cf-48a8-9a2d-0a290135b638" />


## Crime Page
Visuals of crime types by gender. <br>
Total crimes affecting men, women, and children. <br>
Time-based analysis (crimes by hour of day and day of week). <br>
Province-level analysis of crime rates against women. <br>
New calculated columns (hour_of_day, day_of_week) added in Power Query <br>
Key insights: <br>
Women are twice as likely to be victims as men. <br>
Harassment and sexual assault are the most common crimes against women. <br>
Crimes spike on weekends and at night/early mornings. <br>
Amanzi shows lower risk for women compared to other provinces
<img width="1272" height="712" alt="image" src="https://github.com/user-attachments/assets/9f440f02-ebe5-40fd-b442-552843c2f989" />


## Key Takeaways
A multi-star schema was necessary to manage multiple fact tables. <br>
Careful cleaning, fixing relationships, and adjusting filters enabled accurate reporting. <br>
The dashboards provide a layered view of Maji Ndogo’s challenges: water access, queue behavior, pollution, and safety risks. <br>
Interactive filtering lets decision-makers zoom from national patterns to provincial and town-level detail







