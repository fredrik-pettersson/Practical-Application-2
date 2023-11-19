# Practical-Application-2
What drives the price of a used car?  The goal is to analyze a dataset with information on almost half a million used cars to understand what factors make a car more or less expensive. The analysis provides clear recommendations to a used car dealership as to what consumers value in a used car.
# Introduction
An extensive dataset with information on 426,000 used vehicles including price, year, manufacturer, model, condition, engine size (cylinders), fuel, odometer, title status, transmission, VIN, drive, size, type, color, and state was provided by the client who would like to understand what factors drive consumers' willingness to pay
for used vehicles. 
# Methodology
The dataset was analyzed, cleaned, and prepared for machine learning using two different types of multivariable regression models (GridSearchCV with Ridge regression and StandardScaler, and the LinearRegression model with SequentialFeatureSelector). 
The results from these different methods were compared to each other and the relationships between price and the various input variables were visualized. 
Given the size of the dataset and the regional differences in consumer preferences and needs, it was decided to focus on the top 20 car manufacturers and initially target the California market. 
It was also decided to exclude vehicles older than 25 years, as well as motorcycles, vans, buses, offroad vehicles, and commercial vehicles as the focus is on understanding ordinary consumers and their willingness to pay for various features. This methodology can also be used for analyzing used vehicles in other states, 
but this is outside of the scope of this report. 
# Summary: Key Findings and Recommendations
The year of the vehicle is by far the most important feature that determines the price of used cars. Secondary features that drive the price of used vehicles and are attractive for consumers are engine size (number of cylinders), vehicle condition, vehicles with diesel engines, and pickup truck models. 

So, this study recommends that car dealerships apply premium pricing on used vehicles that are newer, have larger engines, and are in good condition, particularly pickup trucks with diesel engines, as consumers are willing to pay more for these features. 
Also, to a lesser degree, there is a willingness to pay more for used Lexus cars, so the recommendation is to sell these at a premium. 

In addition, the results indicate that consumers are less willing to pay for front wheel drive and sedans. 
So, the recommendation here is to avoid buying sedans with front wheel drive, or make sure not to overpay for these vehicles as consumers are clearly less willing to pay for these types of cars. 

The confidence level in the above findings is high. The two regression models outlined in the earlier section gave the same results regarding which are the most important features. These results are also in line with the correlation matrix that was calculated in the early stage of the analysis.

