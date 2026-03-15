# Aviation Accident Analysis

Overview

This project analyzes aviation accident data from 1948–2023 to identify aircraft makes and models that have lower rates of aircraft destruction and lower likelihood of fatal or serious passenger injuries.

The goal is to provide recommendations to an airline insurance client about safer aircraft types.
To focus on aircraft that could still be in service today, the dataset was filtered to include accidents from 1983 onward (assuming a 40-year aircraft lifespan).

The analysis also separates recommendations for small aircraft and large passenger aircraft.


Data Cleaning

Loaded and inspected the dataset using Pandas
Removed missing or irrelevant data
Filtered aircraft accidents to 1983–2023
Created new variables to measure injury severity
Exported the cleaned dataset for analysis


Requirements

pandas 
numpy 
matplotlib
seaborn 

pip install -r requirements.txt

Author
Marco Holt