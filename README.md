# Optimizing Model Prediction

In this project I'd like to practice several techniques to optimize a linear regression model (the techniques however are also transferable to other models).  We will use a dataset from the UCI Machine Learning Repository, the Forest Fires dataset (https://archive.ics.uci.edu/ml/datasets/Forest+Fires). The dataset contains information on fires, along with the resulting damage and associated meteorological data. Our machine learning task will be to predict the damage to a forest from the given data:

- X - x-axis spatial coordinate within the Montesinho park map: 1 to 9
- Y - y-axis spatial coordinate within the Montesinho park map: 2 to 9
- month - month of the year: 'jan' to 'dec'
- day - day of the week: 'mon' to 'sun'
- FFMC - FFMC (Fine Fuel Moisture Code) from the FWI (Fire Weather Index) represents fuel moisture of forest litter fuels under the shade of a forest canopy: 18.7 to 96.20
- DMC - DMC (Duff Moisture Code) from the FWI system represents fuel moisture of decomposed organic material underneath the litter: 1.1 to 291.3
- DC - DC (Drought Code) index from the FWI system represents drying deep into the soil: 7.9 to 860.6
- ISI - ISI (Initial Spread Index) from the FWI system integrates fuel moisture for fine dead fuels and surface windspeed to estimate a spread potential: 0.0 to 56.10
- temp - temperature in Celsius degrees: 2.2 to 33.30
- RH - relative humidity in %: 15.0 to 100
- wind - wind speed in km/h: 0.40 to 9.40
- rain - outside rain in mm/m2 : 0.0 to 6.4
- area - the burned area of the forest (in ha): 0.00 to 1090.84
