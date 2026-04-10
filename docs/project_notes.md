# Project Notes

## Data Cleaning
- Standardized column names
- Removed duplicate records
- Converted birth_date and encounter_date to datetime
- Dropped missing encounter_date

## Feature Engineering
- Created age column
- Created age_group categories
- Extracted encounter_year, month, day

## Data Validation
- Checked missing, zero, negative values in obs_value

## Aggregations
- Created condition_summary (avg obs_value by condition)
- Created monthly_trend dataset

## Output Files
- cleaned_data.csv
- condition_summary.csv
- monthly_trend.csv
- final_dataset.csv
## Visualization

- Created bar chart for average observation value by condition
- Created line chart for monthly trend of observation values
- Saved visual outputs in data/visuals folder
- Used matplotlib for visualization
## Key Insights

- Diabetes patients show higher average observation values compared to hypertension
- Observation values show a consistent trend over time
- Aggregated data helps simplify clinical interpretation

## Tools Used

- Python
- Pandas
- Matplotlib
- VS Code