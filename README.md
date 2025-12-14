# shipping-log-analysis-Capstone_5

# Day 5 Capstone – Shipping Log Analysis

## Scenario

I worked as the MIS Executive for a Global Logistics Company. The VP of Operations needed quick insights from the Shipping_Log file. The goal was to provide answers in less than 5 minutes without sending raw data.

## Dataset

Columns:

* ShipID
* Date
* Priority (High / Med / Low)
* Region
* Cost
* Status (Delivered / Pending / Returned)

## Steps Performed

### 1. Organize Data

* Sorted by Region (A-Z)
* Then by Priority using a custom list: High → Med → Low
* Then by Cost (High → Low)

### 2. Visualize Risks

* Used Conditional Formatting to turn Status red if it says “Returned”
* Added Blue Data Bars to the Cost column for quick visualization

### 3. Prepare Report

* Converted the data into a Table (Ctrl+T)
* Added a Slicer for egion to easily filter

### 4. Answer VP Questions

* Filtered Slicer to West region
* Checked Total Row to get **Total Cost** for West
* Filtered Priority to High to count the number of high-priority shipments

## Excel Skills Used

* Custom Sorting
* Conditional Formatting (cell color + data bars)
* Tables and Total Row
* Slicers for interactive reporting
* Quick filtering and summarization

## Notes

This task demonstrates how to clean, organize, and visualize operational data in Excel to answer executive-level questions quickly.

