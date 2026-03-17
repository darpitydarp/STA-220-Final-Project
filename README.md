# STA 220 Final Project
STA 220 final project that utilizes City of Davis/Eco-Counter bike & scooter counter data, webscrapers of the UC Davis academic calendar, and temperature data from NOAA to model bike & scooter volumes.

## Files and description

### .ipynb files for scraping and analysis
- daily_analysis.ipynb: for regression models of bicycle and scooter counts
- dateScraper.ipynb: for scraping the days of instruction and finals from Davis academic calendar, outputs are in finalsDates.pkl and instructionDates.pkl
- weekly_distribution_clustering.ipynb: for unsupervised clustering of weekly distributions of bicycle and scooter counts

### `data` folder

#### `date pkl` folder
Quarter instruction and finals dates
- finalsDates.pkl: DateTimeIndex object representing all finals dates scraped for the academic years 2018-2019 to 2026-2027
- instructionDates.pkl: DateTimeIndex object representing all dates of academic instruction scraped for the academic years 2018-2019 to 2026-2027
- holidayDates.pkl: DateTimeIndex object representing all holiday dates for the academic years 2018-2019 to 2026-2027

#### `raw` folder
- bike.csv: comma-separated values file with bike counts from the installation of the 3rd St counter from May 25, 2023 to Mar 3, 2026
- scooter.csv: comma-separated values file with scooter counts from the installation of the 3rd St counter from May 25, 2023 to Mar 3, 2026
- temperature.csv: comma-separated values file with bike counts from the installation of the 3rd St counter from May 24, 2023 to Feb 21, 2026