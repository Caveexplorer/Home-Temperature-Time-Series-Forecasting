In this project I execute every step of the data science method to forecast temperature in a home from a variety of measurement data.

This project comes from a competition on kaggle:

https://www.kaggle.com/competitions/smart-homes-temperature-time-series-forecasting/

The point of the project is to be able to forecast the temperature in a particular room in a house using a dataset consisting of about 2000 sets of measurements. The measurements include things like CO2 concentration, relative humidty, irradiance, and light levels from sensors in various places around the house. Predicting temperature will inform a 'smart' HVAC (Heating, Ventilation, Air Conditioning) system whether it needs to turn on to raise or lower the temperature of the house. Raising or lowering temperature by many degrees consumes much more energy than simply maintaining temperature (i.e. activating HVAC for small adjustments in temperature, but more frequently). If we can predict what the temperature will be, perhaps we can avoid those large energy intensive usages of HVAC.

In the Raw Data folder you'll find 'train.csv' which contains the data as it came from kaggle, unaltered by me.

In the Notebooks folder you'll find my work: data wrangling, exploratory data analysis, preprocessing, and modeling. These were all written in Python and in Jupyter Notebooks.

The Data folder contains any altered versions of the original dataset I have made in the course of the project. At there very least, there will be a post data wrangling 'clean' version of the data.