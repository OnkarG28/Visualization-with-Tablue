# Tableau Assignments

This repository contains the completed assignments for various Tableau practice activities. Each assignment focuses on different aspects of data visualization and analysis using Tableau.

## Table of Contents

- [Assignment 1: CDs Analysis](#assignment-1-cds-analysis)
- [Assignment 2: HPIAdmins Data Analysis](#assignment-2-hpiadmins-data-analysis)
- [Assignment 3: HPIRegions Sales Analysis](#assignment-3-hpiregions-sales-analysis)
- [Assignment 4: HPIRegions Volume Analysis](#assignment-4-hpiregions-volume-analysis)
- [Assignment 5: States Population Map](#assignment-5-states-population-map)
- [How to View the Visualizations](#how-to-view-the-visualizations)

## Assignment 1: CDs Analysis

**Objective:** Analyze the CDs dataset to create a bar chart and a line chart, save, close, and reopen the workbook.

**Steps:**
1. Open Tableau and connect to the Excel workbook `SourceDataf.xlsx`, selecting the `CDs` spreadsheet.
2. Create a bar chart showing the smallest file size per `File Extension`.
3. Create a line chart with `Years` and `Quarters` in the Columns shelf and the Minimum of the `#` field in the Rows shelf.
4. Save the visualizations, close Tableau, reopen Tableau, and open the saved file.

## Assignment 2: HPIAdmins Data Analysis

**Objective:** Analyze the HPIAdmins dataset by creating a line chart and a circle display with specific fields and filters.

**Steps:**
1. Connect to the `HPIAdmins` spreadsheet in the `SourceDataf` workbook.
2. Hide all fields except `Date`, `Region Name`, `Index`, and `12m%Change`.
3. Ensure `Date` is a Date field, `Region Name` is a String field, and `Index` and `12m%Change` are number fields.
4. Rename `12m%Change` to "12 month percentage change" and set its default aggregation to Average.
5. Create a line chart showing the average 12 month percentage change per year for each RegionName, with colored lines.
6. Duplicate the viz, change it to a circle display, and add the average of the Index as the size.

## Assignment 3: HPIRegions Sales Analysis

**Objective:** Analyze the HPIRegions dataset by creating various visualizations and adding filters and annotations.

**Steps:**
1. Connect to the `HPIRegions` spreadsheet in the `SourceDataf` workbook.
2. Create a folder for fields starting with "Detached" and move them into that folder.
3. Create a stacked bar chart showing the Date (Year, then Quarter), Sum of SalesVolume as bars, and RegionName as the color.
4. Highlight the West Midlands Region.
5. Add a filter using RegionName, exclude "London" and "England".
6. Create a shape viz with SalesVolume on the bottom, Average of AveragePrice up the graph, RegionName as the color, and Average of 12m%Change as the size. Exclude London and England.
7. Add Date to the Page card (Year and Quarter), labels showing the Minimum and Maximum of the Average of 12m%Change, an annotation in the bottom-right corner saying "House Price inflation by region", change the speed to Fast, and press play.

## Assignment 4: HPIRegions Volume Analysis

**Objective:** Analyze the HPIRegions dataset by creating multiple visualizations and a dashboard.

**Steps:**
1. Connect to the `HPIRegions` spreadsheet in the `SourceDataf` workbook.
2. Create a bar chart showing Year(Date) by SUM(Sales Volume), with Region Name as the Color mark (Viz 1).
3. Create a text viz with Region Name on Rows and Sum(Sales Volume) in Text marks (Viz 2).
4. Create another text viz with Year(Date) on Rows and Sum(Sales Volume) in Text marks (Viz 3).
5. Create a dashboard with Viz 2 in the top-left, Viz 3 in the top-right, and Viz 1 in the bottom half.
6. Use Viz 2 as a filter, click on "East Midlands", then change the filter to work only on a menu. Add a similar filter on Viz 3.
7. Set up the dashboard on a Tablet and a Phone.
8. Create a story using this dashboard three times, each time selecting a different region in Viz 2.

## Assignment 5: States Population Map

**Objective:** Create a map visualization of the population of the 50 US states and identify the top 5 states by population.

**Steps:**
1. Connect to the `States` spreadsheet in the `SourceDataf` workbook.
2. Create a map viz with `Latitude`, `Longitude`, and `Population`.
3. Ensure all 50 states are represented and correct any missing data.
4. Zoom into New York so that it roughly fits the screen.
5. Create a group for states starting with 'M'.
6. Create a text visualization with states sorted by population in descending order.
7. Create a set for the top 5 states by population.
8. Update the map viz to color-code the top 5 states and move the set to the Rows shelf.

## How to View the Visualizations

To view the visualizations:
1. Download and install Tableau Desktop.
2. Clone this repository to your local machine using `git clone <repository-url>`.
3. Open Tableau and connect to the relevant Excel spreadsheets in the `SourceDataf` workbook.
4. Open each Tableau workbook (`.twb` or `.twbx`) file to view the corresponding visualization.


