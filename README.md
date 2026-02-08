Women’s Safety Analytics Dashboard – Real-Time Risk Intelligence
1.Project Motivation

This project was inspired by a real-life experience that highlighted how unsafe everyday environments can feel for women. Safety should not be assumed — it should be measured, analyzed, and improved using data.

This dashboard turns fear into facts and patterns into prevention.

2.Objective

To build a data-driven women safety intelligence system that:

Identifies high-risk zones using historical incident data

Visualizes unsafe hours and crime patterns

Supports informed, safer travel decisions

Lays the foundation for real-time AI-based alerts

3. Key Features

✔ Area-wise, year-wise, and category-wise filters


✔ Heatmaps of safe vs unsafe zones


✔ Time-based risk analysis

✔ Crime severity and response time insights

4.Dataset Overview
1️⃣ https://github.com/shirishasuresh/Women-s-Safety-Analytics-Dashboard-/blob/main/safezone_updated.csv

Contains verified safe locations such as police stations, hospitals, NGOs, and shelters.

Fields:

safezone_id, name, type, city, state, latitude, longitude

contact_number, open_24x7, rating

2️⃣ https://github.com/shirishasuresh/Women-s-Safety-Analytics-Dashboard-/blob/main/safezone_incidents_2022_2024.csv

Contains incident reports near safe zones from 2022 to 2024.

Fields:

incident_id, safezone_id, crime_type, city, state

incident_date, incident_time, severity

reported_to_police, resolved, response_time_minutes

5. Tech Stack

Power BI

CSV datasets

Python (for preprocessing and future ML models)

GitHub

6.Future Scope

AI-based real-time risk prediction

Mobile alert system for unsafe zones

Voice-activated SOS

Women-safe route recommendations

 Final Note

This project is not just dashboards and data — it is an effort to transform awareness into action and fear into protection.
