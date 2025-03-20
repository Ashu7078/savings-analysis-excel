# Savings-analysis-excel

## Overview

This project analyzes participants' savings objectives and common information sources using Microsoft Excel. The analysis includes data summarization using Pivot Tables and visual representation through Donut and Bar Charts.

## Steps to Perform the Analysis

### 1. Importing Data into Excel

- Open Microsoft Excel.
- Click on **File > Open**, then select the provided `bb.csv` file.
- Ensure that the data is structured properly in columns.

### 2. Summarizing Savings Objectives Using Pivot Table

- Click anywhere inside the data table.
- Go to the **Insert** tab and select **PivotTable**.
- Choose **New Worksheet** and click **OK**.
- In the **PivotTable Fields** panel:
  - Drag `What are your savings objectives?` to the **Rows** section.
  - Drag the same field to the **Values** section (set it to **Count**).
- This will generate a summary of savings objectives with their frequencies.

### 3. Visualizing Savings Objectives with a Donut Chart

- Select the Pivot Table results.
- Go to **Insert** tab, then choose **Pie Chart > Donut Chart**.
- Right-click the chart and choose **Add Data Labels** to display percentages.
- Customize colors and labels for clarity.

### 4. Summarizing Information Sources Using Pivot Table

- Click anywhere inside the data table.
- Go to **Insert > PivotTable**.
- Choose **New Worksheet** and click **OK**.
- In the **PivotTable Fields** panel:
  - Drag `Source` to the **Rows** section.
  - Drag `Source` to the **Values** section (set it to **Count**).
- This will generate a summary of common information sources and their frequencies.

### 5. Visualizing Information Sources with a Bar Chart

- Select the Pivot Table results.
- Go to **Insert > Bar Chart > Clustered Bar**.
- Right-click the chart and choose **Add Data Labels**.
- Customize colors, fonts, and gridlines for clarity.

### 6. Saving the Excel File with Visualizations

- Click **File > Save As**.
- Choose **Excel Workbook (.xlsx)**.
- Save the file with a suitable name to include in a report or presentation.

## Conclusion

This analysis provides insights into participants' savings goals and their preferred information sources. Using Pivot Tables and charts makes the data easy to interpret for decision-making and reporting.

## Author: Ashish
