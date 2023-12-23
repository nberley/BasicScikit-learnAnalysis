# BasicScikit-learnAnalysis

## Dataset Overview
This dataset contains the hourly and daily count of rental bikes between the years 2011 and 2012 in the Capital bikeshare system with the corresponding weather and seasonal information.

## Columns in the hour.csv Dataset:
- `instant`: Record index
- `dteday`: Date
- `season`: Season (1: spring, 2: summer, 3: fall, 4: winter)
- `yr`: Year (0: 2011, 1: 2012)
- `mnth`: Month (1 to 12)
- `hr`: Hour (0 to 23)
- `holiday`: Whether the day is a holiday or not (binary)
- `weekday`: Day of the week
- `workingday`: If the day is neither weekend nor holiday (binary)
- `weathersit`: Weather condition (categorical)
- `temp`: Normalized temperature in Celsius
- `atemp`: Normalized feeling temperature in Celsius
- `hum`: Normalized humidity
- `windspeed`: Normalized wind speed
- `casual`: Count of casual users
- `registered`: Count of registered users
- `cnt`: Total count of bike rentals (casual + registered)

## Jupyter Notebook .ipynb
### Key Features
This analysis serves as a basic introduction to running a few different algorithms in Scikit-learn
- Data Exploration: Understanding the characteristics of the data through various statistical techniques.
- Data Visualization: Visual representations of data trends and relationships.
- Preprocessing: Cleaning and preparing the data for modeling.
- Model Building: Implementing machine learning algorithms to predict bike sharing demand.

## Citation
This dataset was provided by Fanaee-T, Hadi. (2013). "Bike Sharing Dataset." UCI Machine Learning Repository. [DOI:10.24432/C5W894](https://doi.org/10.24432/C5W894).
