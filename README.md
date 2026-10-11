# HR Analytics Dashboard Using Excel

## Project Overview

This project explores employee and workforce data in Microsoft Excel.
The workbook includes data-cleaning work, PivotTables, charts, slicers,
and a dashboard for reviewing salary and workforce patterns.

## Tools Used

-   Microsoft Excel
-   Data cleaning
-   PivotTables and PivotCharts
-   Charts and slicers

## Project Workflow

1.  Followed a YouTube tutorial to learn the data-cleaning process.
2.  Applied the demonstrated cleaning steps to prepare the HR dataset.
3.  Created PivotTables to summarize employee and salary information.
4.  Built charts to explore workforce patterns.
5.  Organized the charts and slicers into an HR Analytics dashboard.

## Analysis Included

The workbook contains analysis relating to: - Monthly salary by gender -
Monthly employee hiring by gender - Employee gender distribution -
Employee count by work location and employment type - Department-wise
employee count by gender - Total salary by gender - Department-wise
salary distribution

## Data Quality Notes

During review, the following issues were identified: - 9 records have
`NULL` in the Department field and were flagged as missing. - 4 records
have a salary value of zero and need further investigation. - 4 employee
IDs appear more than once. The repeated records have different salary
values, so they should be investigated rather than automatically
deleted.

These records should not be changed without checking the dataset source
or having a clear rule for how to handle them.

## What I Learned

-   Practiced cleaning and reviewing data in Excel.
-   Used PivotTables to summarize data.
-   Created charts to communicate patterns in HR data.
-   Used slicers to explore dashboard results.
-   Learned the importance of documenting data-quality issues before
    changing records.

## Tutorial Attribution

This project was developed while following a YouTube tutorial.

**Learning Reference:** Chandoo’s Excel tutorials were used as a learning resource. The HR Analytics project was developed by applying the techniques learned to the dataset, creating PivotTables, charts, and an interactive dashboard.


Please credit the original creator and clearly describe any changes or
additional analysis completed independently.

## How to Use the Workbook

1.  Open `HR_Analytics.xlsx` in Microsoft Excel.
2.  Open the main dashboard/report sheet.
3.  Use the available slicers to filter and explore the charts.
4.  Review the supporting sheets for PivotTables and individual charts.

## Future Improvements

-   Investigate the missing department values, zero salaries, and
    repeated employee IDs.
-   Verify that all slicers filter the intended charts.
-   Improve chart-label readability where necessary.
-   Add concise business insights after verifying the dashboard results.
