NJ OCSS Safeguard Program — Mock Tableau Dashboard
====================================================

WHAT THIS IS
------------
A self-contained HTML mockup of what a published Tableau dashboard
would look like for the IRS Pub 1075 Safeguard Inspections program.
Illustrative data only. Not connected to any live Salesforce org.

HOW TO OPEN
-----------
Double-click `index.html` in this folder.
Works in Chrome, Safari, Firefox, and Edge. No install required.
No internet needed after the first load (fonts fall back to system).

CONTENTS
--------
- index.html          The dashboard page
- chart.umd.min.js    Chart.js library (bundled locally, no CDN)
- README.txt          This file

WHAT IT SHOWS
-------------
- 5 KPIs (compliance rate, inspections, open CAPs, overdue, cycle time)
- All 21 NJ counties colored by risk / open CAP count
- 3-year compliance trend
- Findings by IRS Pub 1075 section (§4, §5, §8, §9…)
- CAP lifecycle funnel (Open → In Progress → Verified → Closed)
- Inspector workload distribution
- Monthly seasonality overlay (FY24 / FY25 / FY26)
- Repeat offenders table with chronic findings

QUESTIONS
---------
Ping Mahathi Devulapalli.
