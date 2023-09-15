# Cab Project

Overview
This repository contains code for the Cab Project, which aims to analyze and visualize the demand and supply data of a cab service. The project's primary goals are as follows:

1. 24-hour Curve of Average Demand and Supply Volume: Visualize the 24-hour curve of average demand and supply volume to identify patterns and trends throughout the day.

2. Undersupplied Hours During a Weekly Period (Monday to Sunday): Identify the hours during the week when the demand for cabs exceeds the available supply.

Data Sources
The project utilizes two main data sources:

Demand Side Data.xlsx: Contains data related to demand, including the number of people who saw 0 cars and the number of people who saw more than 1 car.
Supply Side Data.xlsx: Contains data related to supply, specifically the number of active drivers.
Code Structure
The code is written in Python and primarily uses the following libraries:

Pandas: For data manipulation and analysis.
Matplotlib: For creating data visualizations.
NumPy: For numerical operations.
Data Preprocessing
The code includes several data preprocessing steps to clean and prepare the data for analysis:

Removal of unnamed columns.
Conversion of the 'Date' column to datetime format.
Separation of the 'Hour' and 'Date' components.
Analysis and Visualization
24-hour Curve of Average Demand and Supply Volume
The project visualizes the 24-hour curve of average demand and supply volume. It identifies points where demand exceeds supply and annotates these points on the graph. This analysis helps in understanding peak demand hours.

Undersupplied Hours During the Week
The project analyzes and visualizes the average demand and supply data for each day of the week (Monday to Sunday). It highlights the hours during which the demand exceeds the supply, indicating potential undersupplied periods.

Running the Code
To run the code and replicate the analysis, follow these steps:

Ensure you have the required Python libraries (Pandas, Matplotlib, NumPy) installed.
Download the Demand Side Data.xlsx and Supply Side Data.xlsx files and update the file paths in the code accordingly.
Execute the Python script, and the analysis and visualizations will be generated.
Results
The results of this project provide valuable insights into the demand and supply dynamics of the cab service, helping in better resource allocation and decision-making.
