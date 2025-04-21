# Mall Customer Segmentation

### Core Cleaning Steps:
Cleaned and processed the "Mall Customer Segmentation" dataset using Excel. This included:
- Handled missing values using filters
- Removed duplicate rows
- Standardized text fields (e.g., gender)
- Converted inconsistent date and text formats
- Renamed column headers to be clean and uniform
- Checked and corrected data types

### Advanced Steps:
- Created a new **Age Group** column using Excel formula:
  '''excel'''
  =IF(D2>55, "SENIOR", IF(D2>25, "ADULT", "TEEN"))

## Visualizations
- Gender vs Spending Score (pie Chart)
- Age Group vs Spending Score (Column Plot)

## Files Included
- `cleaned_data.csv`: Final cleaned dataset
- `raw_data.csv`: Original dataset
- `charts/`: Screenshots of charts
- `README.md`: This file

## Tools Used
- Microsoft Excel
- GitHub
- Data: Mall Customer Segmentation Dataset (Kaggle)

## Learnings
- Gained hands-on experience in data cleaning
- Practiced creating charts in Excel for customer analysis
- Learned how to structure and present a project in GitHub
