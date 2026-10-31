# California_Forest_Fire_Description_Dashboard
Interactive Power BI dashboard analysing California wildfire incidents from 2014–2023. Tracks acres burned, homes destroyed, injuries, fatalities and financial loss by cause, location and year, with KPI cards, slicers, a map view and bookmarks. Built using Power Query and custom theming.

# 🔥 California Forest Fire Dashboard (Power BI)

An interactive Power BI dashboard that explores California wildfire incidents
from 2014 to 2023, covering environmental, human and economic impact.

## 📌 Overview
The dashboard helps answer:
- Which causes burn the most land and cause the most harm?
- Which locations are hit hardest?
- How have incident counts changed over time?
- What are the total human and financial costs?

## 📂 Dataset
- File: `California Wildfire Damage.csv` (100 incidents, 11 columns)
- Fields: Incident_ID, Date, Location, Area_Burned (Acres), Homes_Destroyed,
  Businesses_Destroyed, Vehicles_Damaged, Injuries, Fatalities,
  Estimated_Financial_Loss (Million $), Cause
- Period: Feb 2014 – Dec 2023 | 10 locations | 3 causes
- Note: sample/simulated dataset for learning purposes

## 🖥️ Report Pages
1. **Dashboard** – KPI cards (injuries, acres burned, homes destroyed,
   fatalities, incidents), slicers (date hierarchy, cause), area burned by
   cause, deaths by cause, incidents over time, incidents by location,
   and a location detail table.
2. **Map** – Injuries by location, sized by injuries, with acres burned
   and fatalities in the tooltip.
3. **Bookmark** – Alternate views (fatalities, homes destroyed,
   year-by-year incidents) navigated with buttons.

## 🔎 Key Insights
- Total: 2.65M acres burned, 94,189 homes destroyed, 4,204 injuries,
  993 fatalities, ~$239.6B estimated loss.
- Human activity: 38% of incidents, most acres burned (1.05M) and highest loss.
- Shasta County: most incidents (14) and highest loss ($37.2B).
- Mendocino County: most injuries (687) and homes destroyed (13,166).
- 2021 and 2014 had the most incidents (13 each); 2017 had the fewest (5).

## 🛠️ Tools & Techniques
· MS Excel · Power BI Desktop · Power Query · Date hierarchy · Slicers · Bookmarks ·
Map visual · Tooltips · Custom theme

## 👤 Author
Ayush Pundir · https://www.linkedin.com/in/ayush-pundir-131022268
