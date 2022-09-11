# PyBer-Analysis

## Overview

In this module, the *Python's Pandas* and *Python's Matplotlib* libraries are used to process, analyze and visualize PyBer's ride-sharing data.

Two input csv datasets are provided for its analysis:

1.Ride-sharing information by city, **[city data](./Resources/city_data.csv)**.

![Image 01](./analysis/Image01_city_data.jpg)

*Image 01: Input city data (sample rows).*

2.Ride-sharing information by ride, **[ride data](./Resources/ride_data.csv)**.

![Image 02](./analysis/Image02_ride_data.jpg)

*Image 02: Input ride data (sample rows).*

The objectives are to showcase the relationship between the type of city and the number of drivers and riders as well as the percentage of total fares, riders and drivers for each type of city. The results being produced will help PyBer improve the acces to ride-sharing services and assess the affordability for underserved neighborhoods.

The **[analysis jupyter notebook](./PyBer_Challenge.ipynb)** along with the following three final deliverables are provided:

- **[Deliverable 1](./analysis/Deliverable1_SummaryDF.jpg)**: A ride-sharing summary DataFrame by city type.
- **[Deliverable 2](./analysis/Deliverable2_LineChart.jpg)**: A multiple-line chart of total fares for each city type.
- **Deliverable 3**: A written report for the PyBer analysis (This README.md file).

## Results

### **Deliverable 1: Ride-sharing Summary DataFrame by City**

The first step to generate the ride-sharing summary dataframe consisted in merging the two input tables based on the name of the city, this is because the *city* column is the only one shared by both.  

![Image 03](./analysis/Image03_merged_table.jpg)

*Image 03: Merged input data (sample rows).*

In order to create the summary table, first, the total number of rides and drivers per city type were calculated. Note that there are three city types, rural, suburban and urban and the total fare amount is also computed for all of them, this is, the sum of all the fares of each city. Finally, the average fare per ride & driver were calculated by dividing the total fare per city type over the total number of rides & drivers per city type respectively.

![Image 04](./analysis/Deliverable1_SummaryDF.jpg)

*Image 04: Deliverable 1: ride-sharing summary DataFrame by city type.*

## Summary

s
