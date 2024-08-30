# Exploratory Data Analysis on Electric Vehicle Population

This project analyzes the population of electric vehicles (EVs) across various counties and cities. The data is derived from a dataset containing detailed information about EVs, including make, model, type, and location.

## Table of Contents
- [Exploratory Data Analysis on Electric Vehicle Population](#exploratory-data-analysis-on-electric-vehicle-population)
  - [Table of Contents](#table-of-contents)
  - [Project Goals](#project-goals)
  - [Data Description](#data-description)
  - [Project Objectives](#project-objectives)

## Project Goals

The goal of this project is to analyze and visualize the Electric Vehicle Population dataset from Kaggle using Python libraries such as Matplotlib, Seaborn, and Plotly.

The project involves the following steps:

1. **Download the Dataset:** Obtain the Electric Vehicle Population dataset from Kaggle and convert it into a pandas dataframe.
2. **Data Cleaning:** Perform data cleaning and handle missing values using Pandas and NumPy.
3. **Data Visualization:** Create interactive graphs to understand the data using visualization libraries like Plotly.
4. **Exploratory Data Analysis (EDA):** Explore the dataset, ask interesting questions, and use visualizations to uncover insights.

## Data Description

These are the column/attribute descriptions to help understand the data:

1. **VIN (1-10):** The first 10 characters of the Vehicle Identification Number.
2. **County:** The county where the vehicle is registered.
3. **City:** The city where the vehicle is registered.
4. **State:** The state where the vehicle is registered (all values are likely "WA" for Washington State).
5. **Postal Code:** The postal code corresponding to the vehicle’s registration location.
6. **Model Year:** The year the vehicle was manufactured.
7. **Make:** The manufacturer of the vehicle (e.g., Tesla, Chevrolet).
8. **Model:** The model name of the vehicle (e.g., Model 3, Volt).
9. **Electric Vehicle Type:** Indicates whether the vehicle is a Battery Electric Vehicle (BEV) or a Plug-in Hybrid Electric Vehicle (PHEV).
10. **Clean Alternative Fuel Vehicle (CAFV) Eligibility:** Indicates whether the vehicle is eligible for a clean alternative fuel vehicle program.
11. **Electric Range:** The range (in miles) the vehicle can travel on electric power alone.
12. **Base MSRP:** The manufacturer’s suggested retail price for the base model of the vehicle.
13. **Legislative District:** The legislative district where the vehicle is registered.
14. **DOL Vehicle ID:** A unique identifier assigned by the Department of Licensing (DOL).
15. **Vehicle Location:** Geographic coordinates (longitude and latitude) of the vehicle’s registration.
16. **Electric Utility:** The electric utility company serving the area where the vehicle is registered.
17. **2020 Census Tract:** The 2020 Census Tract corresponding to the vehicle’s registration location.

## Project Objectives

The main objectives of this project are:

1. Which counties have the highest number of electric vehicles (EVs)?
2. Which cities have the highest number of electric vehicles (EVs)?
3. Who are the top 10 EV manufacturers?
4. What are the top 10 EV models?
5. What is the count and percentage distribution of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs)?
6. What is the trend of EV sales over the years?
7. What is the count and percentage distribution of Clean Alternative Fuel Vehicles (CAFVs)?
8. What is the average range of different makes?
9. Which are the top 10 makes by average range?
10. Which are the top 10 makes with the highest number of vehicles in the top 10 counties?
11. Which are the top 10 models with the highest number of vehicles in the top 10 counties?
12. Which are the top 10 makes with the highest number of vehicles in the top 10 cities?
13. Which are the top 10 models with the highest number of vehicles in the top 10 cities?
14. What are the top models of the top make by vehicle count?
15. What is the electric range of Tesla models?
