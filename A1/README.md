#HCDE410
Files for HCDE410 - Assignment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data
# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St
**Source:** https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bicycle-Cou/2z5v-ecg8/about_data  (pulled 2026-10-07)
**License / terms of use:** Data provided by City of Seattle, Public Domain

## Questions I asked
- **Q1. Peak traffic hours:** When is the Burke-Gilman Trail busiest and quietest across the day, combining bike and pedestrian traffic?
- **Q2. Usage breakdown:** How do the usage patterns, peaks, and quiet periods differ between cyclists and pedestrians?
- **Q3. Commuting vs. recreation:** Is there evidence of a weekday commuting pattern versus weekend leisure use across different times of day?
- **Q4. Direction and flow:** Does directional traffic (northbound vs. southbound) change between morning and evening hours, and what does this reveal about trip destinations?

## How to re-run
Open `A1.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).
All data is pulled dynamically through the City of Seattle Socrata API query in Part 0.