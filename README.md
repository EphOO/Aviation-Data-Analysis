# Aviation-Data-Analysis
Exploratory data ananlysis on flight operation to identify patterns, price differences on departure and arrival time,, distance, departure and arrival time, interactive visual analysis of flight routes and performance metrics.
# Overview
This project explores and analyzes flight operatons data to uncover insights about airline perfomance, routes, traffic trends. The goal is to demonstrate practical data analysis skills; from data cleaning, data exploration, and insight reporting using real world aviation datasets.
# Objective
Analyze flight trends by airline, route, and time period
Identify price variation among diffent airlines
Identify the price difference between the Economy class and Business
Build a foundation for future predictive modeling (price prediction)
# Tools & Technologies
Language = Python

Data Analysis = Numpy, Pandas

Visualization = Matplotlib, Seaborn, Relplot

Data Cleaning = Pandas

Enviroment = Jupyter Notebook
# Dataset Source
The source of the dataset is kaggle(Flight Dataset)
# Key Analysis Steps
## Data Cleaning
The data is clean, deviod of any missing values, so I just head to EDA.
## EXploratory Data Analysis
Summary tatistics by airline, route, departure city, destination city.

Correlation between ticket price of Economy class and Business class.

How is the price affected when tickets are ought in just 1 or 2 days before departure

How the price changes with change in the Source City and Destination

Does Departure and Arrival Time affect Ticket Price

What will be the average price of Vistara airline for a flight from Delhi to Hydrabad in Business class

How does the ticket price vary between the Economy and Business class
# Visualization
Bar and barplot for Departure and Arrival Time Ticket Price
Catplot for variaton between Price and differnt Airline
# Insights and Findings
Flight booked a few days before departure are more expensive than those booked earlier.

Flights with late-night departure are the cheapest, while flights with night depatures are the most expensive with about ~59%

Flights with late-night arrivals are the cheapest, while flight with evening arrivals are the most expensive with about ~51%

