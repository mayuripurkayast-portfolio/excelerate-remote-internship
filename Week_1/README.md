# Week 1 — Dataset Familiarization & Team Charter
 
*Impact Makers (Team 5) · DePaul University International Student Admissions Project*
 
## What's in this folder
 
- `Team_Charter_Impact_Makers.pdf` — team roles, mission, and working agreements
- `Exploratory_Analysis_of_DePaul_University.pdf` — first look at the raw dataset and its quality issues
## Team Charter Summary
 
Four-person team supporting DePaul University's admissions data project, coordinated with sponsor associate Richard Oppong Kwarteng.
 
| Member | Role |
|---|---|
| Rahul Dhanda | Team Lead — sponsor liaison |
| Mayuri Purkayasth | Project Manager — guidance & insight synthesis |
| Souvik Saha | Project Scribe — meeting notes & assignments |
| Funke Obatuyi | Project Lead — deadline accountability |
 
**Mission:** turn raw applicant data into clear insights through cleaning, exploration, and simple visuals to support better admissions decisions.
 
## Exploratory Analysis Summary
 
Initial review of the raw dataset — a university admissions CRM export that was not yet analysis-ready.
 
| Metric | Finding |
|---|---|
| Total records | 7,543 applications |
| Total columns | 80 variables |
| Empty columns | ~30+ with no usable data |
| Duplicate/redundant fields | Multiple (e.g. `University`, `Created_At` repeated) |
 
## Key Early Insights
 
- **Geographic concentration:** India dominates with 4,488 applicants, far ahead of the US (750) and Ghana (440)
- **University concentration:** Osmania University leads with 266 students, well ahead of the next tier
- **Data quality:** duplicate Reference_IDs, integer-stored timestamps, and merged/inconsistent fields flagged for cleaning
---
 
Next: see [`week2`](../week2) for the full data cleaning process.
 
