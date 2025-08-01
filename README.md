# Airline Data Management and Analysis Using Power BI

## Project Title
Airline Data Management and Analysis Using Power BI

## Problem Statement
The airline industry operates with numerous complexities, requiring effective data management and insights into flight schedules, passenger details, and ticketing systems. This project aims to analyze airline operations for improving efficiency and customer satisfaction.

## Datasets Used
- **Flight Information:** FlightID, FlightNumber, Airline, Destination, Status  
- **Passenger Information:** PassengerID, FlightID, SeatNumber  
- **Ticket Information:** TicketID, FlightID, BookingStatus

## Objective
To analyze and visualize airline data for operational insights, passenger management, and ticket booking trends using Power BI.

## Tasks and Deliverables

### 1. Data Preparation and Cleaning 
- Extract and transform data in Power Query.
- Clean data: remove duplicates, handle missing values, and format columns.
- **Deliverable:** Screenshot of Power Query Editor showing cleaned data.

### 2. Data Modeling 
- Create relationships between datasets (FlightID as the key).
- Understand cardinality and configure the model appropriately.
- **Deliverable:** Screenshot of the data model with relationships.

### 3. Enhanced Data Insights 
- Add a conditional column to classify flights as "Best" or "To Be Improved" based on status.
- Use "Column from Examples" to extract the flight number from FlightNumber.
- **Deliverable:** Screenshot of the transformed data.

### 4. Calculations Using DAX 
- Calculate:
  - Total passengers for a specific flight.
  - Total tickets booked.
  - Filtered table showing "Best" flights only.
- **Deliverable:** Screenshot of DAX calculations and results.

### 5. Visualization and Interactive Features 
- Create visuals for:
  - Passenger count by airline.
  - Ticket booking statuses.
  - Flights by airline and destination.
- Add interactive features for:
  - Destination and Airline.
  - Quick views.
  - Airline-specific pages.
- **Deliverable:** Screenshots of all visuals and interactive features.

### 6. Final Dashboard and Power BI Service (20 Marks)
- Design a comprehensive dashboard with key visuals and insights.
- Configure Row-Level Security (RLS) for Airline A data and assign it to a user.
- Set up a schedule refresh at 5 PM daily.
- **Deliverable:** Screenshot of the published dashboard and RLS configuration.
