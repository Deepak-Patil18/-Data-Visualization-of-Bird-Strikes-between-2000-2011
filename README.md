# Data-Visualization-of-Bird-Strikes-between-2000-2011
# Bird Strike Data Analysis Project

## Overview

This project explores a dataset of bird strike incidents between 2000 and 2011 to understand patterns and factors influencing these events. The analysis focuses on visualizing trends and relationships within the data.

## Technologies Used

* Pandas
* Numpy
* Matplotlib
* Seaborn
* missingno
* openpyxl

## Questions Answered

* How are bird strike incidents distributed over the years?
* What types of aircraft are most frequently involved in bird strikes?
* How does the presence of pilot warnings relate to the effect of bird strikes on flights?
* What is the pattern of missing values in the dataset?

## Data Exploration

The dataset includes the following columns:

* `Record ID`: Unique identifier for each incident
* `Aircraft: Type`: Type of aircraft (e.g., Airplane, Helicopter)
* `Airport: Name`: Name of the airport where the incident occurred
* `Altitude bin`: Altitude range of the incident
* `Aircraft: Make/Model`: Make and model of the aircraft
* `Wildlife: Number struck`: Number of birds struck (textual categories)
* `Wildlife: Number Struck Actual`: Actual number of birds struck
* `Effect: Impact to flight`: Effect of the strike on the flight (e.g., Engine Shut Down)
* `FlightDate`: Date of the incident
* `Effect: Indicated Damage`: Indicated damage to the aircraft
* `...` (and other columns as needed - list the ones you use in your analysis)

## Key Findings

* Bird strike incidents show [Add findings here based on the analysis in the notebook, e.g., "a general increase between 2000 and 2011", "Airplanes are the most frequently involved aircraft type"].
* Pilot warnings [Add findings here, e.g., "do not completely eliminate severe incidents but may reduce their likelihood"].
* Missing data is [Add findings here, e.g., "concentrated in certain columns like 'Effect: Impact to flight'"].

## Visualizations

* Histograms showing the distribution of bird strikes by year.
* Bar charts comparing the number of bird strikes by aircraft type.
* Stacked bar charts showing the relationship between pilot warnings and the effect of bird strikes on flight.
* Missing value matrix from `missingno` to visualize missing data patterns.
* [Add other visualizations and their interpretations if available]

## Conclusion

[Add a summary of the analysis and its implications, e.g., "This analysis highlights the increasing trend of bird strike incidents, emphasizing the need for better prevention strategies. The relationship between pilot warnings and incident severity suggests that while warnings are helpful, other factors are also critical." ]
