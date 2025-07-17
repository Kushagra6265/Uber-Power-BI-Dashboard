# Uber Trip Analysis Dashboard

## Project Overview
This project involves analyzing Uber trip data using Power BI to gain insights into booking trends, revenue, and trip efficiency. The goal is to help stakeholders make data-driven decisions.

## Business Requirements
### Dashboard 1: Overview Analysis
- Analyze Uber trip data to gain insights into booking trends, revenue, and trip efficiency.

### Key Performance Indicators (KPIs)
1. **Total Bookings**: How many trips were booked over a given period?
2. **Total Booking Value**: What is the total revenue generated from all bookings?
3. **Average Booking Value**: What is the average revenue per booking?
4. **Total Trip Distance**: What is the total distance covered by all trips?
5. **Average Trip Distance**: How far are customers traveling on average per trip?
6. **Average Trip Time**: What is the average duration of trips?

### Expected Outcomes
- Identify trends in ride bookings and revenue generation.
- Analyze trip efficiency in terms of distance and duration.
- Compare booking values and trip patterns across different time periods.
- Provide insights to optimize pricing models and improve customer satisfaction.

## Dashboard Features
### Measure Selector
- Create a Measure Selector using a Disconnected Table with the following values:
  - Total Bookings
  - Total Booking Value
  - Total Trip Distance
- Use a measure to dynamically update visualizations based on user selection.

### Additional Enhancements
- **Dynamic Title**: Update the chart title based on the selected measure.
- **Slicers**: Add filters for Date, City, and other interactive filters for deeper analysis.
- **Tooltips**: Show additional details like Average Booking Value or Trip Distance.

### Vehicle Type Analysis
- Create a grid table (matrix or table visual) to analyze KPIs across different Vehicle Types in Uber trips.
- Apply Conditional Formatting to highlight high and low values.
- Enable Sorting & Filtering for user interaction.

### Total Bookings by Day
- Detect trends and fluctuations in daily trip volumes.
- Identify peak and off-peak booking days.
- Understand the impact of external factors (holidays, events, weather) on ride demand.

### Location Analysis
- **Most Frequent Pickup Point**: Identify the most common starting locations for trips.
- **Most Frequent Drop-off Point**: Find the most common drop-off locations.
- **Farthest Trip**: Determine the longest trip based on distance travelled.
- **Total Bookings by Location (Top 5)**: Identify the top 5 locations with the highest trip bookings.
- **Most Preferred Vehicle for Location Pickup**: Determine the most frequently booked vehicle type at each pickup location.

## Other Implementation Enhancements
- **Bookmark for Data Details**: Add a "Data Details" bookmark to explain key metrics and data sources.
- **Clear Slicer Button**: Add a "Clear Filters" button for quick dashboard resets.
- **Download Raw Data Button**: Enable users to export raw data in CSV or Excel format.

## Dashboard 2: Time Analysis
- Analyze ride demand and trends across different time intervals to optimize operations, pricing, and driver availability.

### Global Dynamic Measure
- A measure selector will be created for:
  - Total Bookings
  - Total Booking Value
  - Total Trip Distance

### Visualizations
- **By Pickup Time (10-Minute Intervals)**: Area Chart to identify peak and off-peak demand periods.
- **By Day Name**: Line Chart to analyze weekday vs. weekend demand.
- **By Hour and Time**: Heatmap (Matrix Grid) to highlight peak booking hours across different days.

## Dashboard 3: Details Tab
- Provide in-depth insights and allow users to explore granular data.

### Features of the Grid Tab
- **Grid Table with Key Fields**: Displays essential trip details.
- **Drill-Through Functionality**: Users can right-click on a data point to access detailed records.
- **Bookmark for Full Data View**: Toggle between filtered drill-through data and the complete dataset.

## Conclusion
This project aims to provide comprehensive insights into Uber trip data, enabling stakeholders to make informed decisions based on data analysis.

## Screenshots
<img width="1309" height="734" alt="Screenshot 2025-07-17 222437" src="https://github.com/user-attachments/assets/0a60e5ac-ec1a-4366-8303-573a04a9065b" />
<img width="1308" height="735" alt="Screenshot 2025-07-17 222500" src="https://github.com/user-attachments/assets/557e8f94-6d69-4acb-9184-c9df5389ef0e" />
<img width="1299" height="736" alt="Screenshot 2025-07-17 222518" src="https://github.com/user-attachments/assets/1d4fc829-1c85-460e-acba-9abe8dd54c2f" />




