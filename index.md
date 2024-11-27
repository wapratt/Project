# AIN'T GONNA RAIN NO MORE
## Relationships between the Palmer Drought Severity Index and Soil Moisture
Final Project for CLIM 680: Climate Data  
Aaron Pratt developed this site  
Fall 2024

# Introduction
Water is vital to human systems, including agricultural production. Drought is a period of drier than normal conditions, or limited water. Soil moisture, or water available for plants to use in their growth, is critical for crop production. Understanding spatial relationships of drought periods and soil moisture available for crop growth can assist in planning agricultural production.

# Data

## Drought: 

***Palmer Drought Severity Index:*** identifies relative wet or dry conditions based on temperature, precipitation, and soil-water holding capacity

Source: https://psl.noaa.gov/data/gridded/data.pdsi.html

Spatial Resolution: 2.5 degrees

Temporal Resolution: Monthly

Variable of Interest: Palmer Drought Severity Index

Timespan: January 1870 to December 2005

## Soil Moisture

***Climate Prediction Center Soil Moisture V2:*** models soil moisture based on monthly precipitation and temperature

Source: https://psl.noaa.gov/data/gridded/data.cpcsoil.html

Spatial Resolution: 0.5 degrees

Temporal Resolution: Monthly

Variable of Interest: Soil Moisture in millimeters

Timespan: January 1948 to October 2024

# Code Description

# Results

I began with exploration of the drought climatology and anomalies at a point in Washington, DC. We observe in this chart periods of relative moisture and drought that can span several months. The signal of periods of relative moisture and drought persist even across a year or 5 year running averages. The intensity of the relative moisture can vary, though the averages decrease the intensity relative to monthly patterns.

![Drought anomalies in Washington, DC](dc_drought_anom.png)
Figure 1: Drought anomalies in Washington DC

I brought in the soil moisture anomaly data at that same point to begin to review the relationship between drought and soil moisture.   
![Drought and soil across time in Washington, DC](dc_drought_soil.png)


To und
![Drought cycles](drought_cycle.png)
Figure 2: Periods of relative drought, moisture, and neutral water regime, based on an index threshold of 0.5.


![Soil componsite based on drought cycles](drought_soil_comp.png)

![Soil and drought correlation](drought_soil_corr.png)

![Soil linear regression based on drought](drought_soil_linr.png)



# Summary
