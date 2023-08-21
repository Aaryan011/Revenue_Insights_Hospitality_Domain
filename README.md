# Revenue Insights | Hospitality Domain

![AtliQ Grands](images/Thumbnail1.png)

Welcome to the AtliQ Grands Revenue Insights project repository! In this project, I have implemented data analytics using Power BI to empower AtliQ Grands with the ability to make data-driven decisions, surpass competitors in the market, and drive growth in various aspects like Market Share & Revenue

You can watch the presentation video here

## Table of Contents

- [Introduction](#introduction)
- [Company Background](#company-background)
- [Problem Statement](#problem-statement)
- [Tech Stacks](#tech-stacks)
- [Business Terminology](#business-terminology)
- [Dataset](#dataset)
- [Dashboard](#dashboard)
- [Insights](#insights)

## Introduction

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years.

## Company Background

AtliQ Grands own multiple five-star hotels across the following cities.

| City       | Category | Property Name       |
|------------|----------|----------------------|
| Delhi      | Luxury   | AtliQ Grands        |
|            |          | AtliQ Blu           |
|            |          | AtliQ Bay           |
|            | Business | AtliQ City           |
|            |          | AtliQ Palace         |
| Mumbai     | Luxury   | AtliQ Exotica       |
|            |          | AtliQ Bay           |
|            |          | AtliQ Blu          |
|            |          | AtliQ Grands           |
|            |          | AtliQ Exotica           |
|            | Business | AtliQ Palace         |
|            |          | AtliQ Seasons          |
|            |          | AtliQ City          |
| Hyderabad  | Luxury   | AtliQ Blu           |
|            |          | AtliQ Bay           |
|            |          | AtliQ Exotica         |
|            |          | AtliQ Grands       |
|            | Business | Atliq Palace          |
|            |          | AtliQ City        |
| Bangalore  | Luxury   | AtliQ Grands        |
|            |          | AtliQ Bay           |
|            |          | AtliQ Blu          |
|            |          | AtliQ Exotica         |
|            | Business | AtliQ City           |
|            |          | AtliQ Palace         |


## Problem Statement

AtliQ Grands owns multiple five-star hotels across India. 
They have been in the hospitality industry for the past 20 years. 
Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. 
As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue.

Task:
- Create the metrics according to the metric list.
- Create a dashboard according to the mock-up provided by stakeholders.
- Create relevant insights that are not provided in the metric list/mock-up dashboard.

## Tech Stacks

- MS Excel
- Power BI
- Power BI Service
- DAX

## Business Terminology

In the hotel industry, several key metrics are crucial for assessing performance and making informed decisions. Here's a brief explanation of some of these metrics:

- **ADR (Average Daily Rate)**: ADR represents the average price charged for each room per day. It's calculated by dividing total room revenue by the number of rooms sold.

- **Average Rating**: This is an average score or rating given by guests based on their stay experience, often derived from guest reviews and surveys.

- **DBRN (Daily Booked Room Night)**: This metric tells on average how many rooms are booked for a day considering a time period.
  
- **DSRN (Daily Sellable Room Night)**: This metric tells on average how many rooms are ready to sell for a day considering a time period.

- **DURN (Daily Utilized Room Night)**: This metric tells on average how many rooms are successfully utilized by customers for a day considering a time period.

- **Occupancy (%)**: Occupancy percentage calculates the ratio of occupied rooms to total available rooms, a key performance indicator.

- **No Show Rate (%)**: This metric reveals the percentage of guests who make reservations but fail to arrive at the hotel as scheduled.

- **Realisation (%)**: It is nothing but the successful "checked out" percentage of all bookings that happened.

- **Revenue**: Total revenue generated by the hotel, encompassing income from various sources like room bookings, dining services, and events.

- **RevPAR (Revenue per Available Room)**: RevPAR represents the revenue generated per available room, whether or not they are occupied. RevPAR helps hotel measure their revenue-generating performance to accurately price rooms. RevPAR can help hotels measure themselves against other properties or brands. 

These metrics play a vital role in hotel management, aiding in pricing optimization, resource allocation, and enhancing overall guest satisfaction. Understanding and monitoring these metrics are essential for a hotel's success.

## Dataset

Below is an overview of the dataset. It consists of three dimensions (dim) files and two fact files:

| File Name                | Description                |
|--------------------------|----------------------------|
| dim_date     | Contain Dates, Week numbers, and Day Types ( Weekday/Weekend ).   |
| dim_hotels        | Contains Property ID, Property Names, Locations, and Categories of hotels.  |
| dim_rooms        | Contains various room types: Standard, Elite, Premium, and Presidential.  |
| fact_bookings       | Contains booking details, including Booking ID, Property ID, Booking Date, Check-in Date, Check-out Date, Number of Guests, Room Category, Booking Platform, Ratings Given, Booking Status, Revenue Generated, and Revenue Realized. |
| fact_aggregated_bookings       | Contains aggregated property bookings data, including Property ID, Check-in Date, Room Category, Capacity, and Successfully Booked Rooms. |




