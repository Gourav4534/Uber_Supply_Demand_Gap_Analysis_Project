# Uber Supply-Demand Gap Analysis Project

This project aims to analyze the supply-demand gap for Uber services using a dataset containing customer requests, driver availability, and trip status. The analysis provides insights into the patterns of trip completion, cancellations, and instances where no cars are available, helping to identify the most problematic time slots and locations for Uber's service.

### Project Overview
The dataset consists of 6745 Uber requests with attributes such as request ID, pickup point, driver ID, request status, and timestamps for request and drop. The analysis focuses on identifying trends and patterns in these requests to understand the supply-demand dynamics better.

### Data Description
The dataset contains the following columns:

- Request ID: Unique identifier for each request.
- Pickup point: Location of pickup (City or Airport).
- Driver ID: Unique identifier for each driver.
- Status: Status of the request (Trip Completed, Cancelled, No Cars Available).
- Request timestamp: Timestamp when the request was made.
- Drop timestamp: Timestamp when the trip was completed.

### Analysis Highlights
1. Data Cleaning and Preprocessing:
Converted timestamp columns to datetime format.
Extracted additional features like request date, request hour, request day, and time slot.

2. Request Status Segmentation:
Overall request status breakdown.
Status segmentation based on pickup point and time slots.

3. Supply-Demand Gap Analysis:
Identified time slots with the highest gaps between supply and demand.
Analyzed trends based on hourly and time slot data.

4. Visualizations:
Bar plots for request status segmentation.
Line plots for hourly and time slot-based supply-demand trends.

### Key Findings
* High Cancellation Rates: Significant number of cancellations for city pickups.
* No Cars Available: High frequency of no cars available status for airport pickups.
* Peak Problematic Time Slots: Morning (5 AM to 9 AM) and Evening (5 PM to 9 PM) show the highest supply-demand gaps.
  
## Visualizations
Here are some key visualizations from the analysis:

* Overall Request Status Segmentation: Shows the percentage of completed trips, cancellations, and no cars available.
* Request Status Segmentation by Pickup Point: Highlights differences in request statuses based on city and airport pickups.
* Hourly Supply-Demand Gap: Line plot showing demand, supply, and the gap trend throughout the day.
* Time Slot Supply-Demand Gap: Analysis of supply-demand gap across different time slots.

##  Conclusion
This analysis provides valuable insights into Uber's supply-demand dynamics, highlighting the critical periods and locations where the service faces challenges. By understanding these patterns, Uber can implement strategies to improve driver availability and reduce customer denials, enhancing overall customer satisfaction.
