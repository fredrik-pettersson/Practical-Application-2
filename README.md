# Practical-Application-2
What drives the price of a used car?  The goal is to analyze a dataset with information on almost half a million used cars to understand what factors make a car more or less expensive. The analysis provides clear recommendations to a used car dealership as to what consumers value in a used car.
# Introduction
An extensive dataset with information on 426,000 used vehicles including price, year, manufacturer, model, condition, engine size (cylinders), fuel, odometer, title status, transmission, VIN, drive, size, type, color, and state was provided by a car dealership client who would like to understand what factors drive consumers' willingness to pay for used vehicles. A total of 55 different features and their impact on used vehicle pricing were analyzed in the study. 
# Methodology
The dataset was analyzed, cleaned, and prepared for machine learning using two different types of multivariable regression models: GridSearchCV with Ridge regression and StandardScaler, and the LinearRegression model with SequentialFeatureSelector.

The results from these different methods were compared to each other and the relationships between price and the 55 different input variables were visualized. 
Given the size of the dataset and the regional differences in consumer preferences and needs, it was decided to focus on the top 20 car manufacturers and initially target the California market. Also, a large amount of the samples in the database were incomplete and missed critical information. To ensure high quality conclusions,
these incomplete samples were removed from the analysis. 

It was also decided to exclude vehicles older than 25 years, as well as motorcycles, vans, buses, offroad vehicles, and commercial vehicles as the focus is on understanding ordinary consumers and their willingness to pay for various features. This methodology can also be used for analyzing used vehicles in other states, 
but this is outside of the scope of this report. 
# Summary: Key Findings and Recommendations
The year of the vehicle is by far the most important feature associated with higher pricing of used cars. Secondary features associated with a higher price are engine size (number of cylinders), vehicle condition, vehicles with diesel engines, and pickup trucks. 

This study recommends that car dealerships apply premium pricing on used vehicles that are newer, have larger engines, and are in good condition, particularly pickup trucks with diesel engines, as consumers are willing to pay more for these features. 
Also, to a lesser degree, there is a willingness to pay more for used Lexus cars, so the recommendation is to sell these at a premium. 

In addition, the results indicate that consumers are less willing to pay for front wheel drive and sedans. 
Therefore, the recommendation here is to avoid building an inventory of too many traditional sedans with front wheel drive and make sure not to overpay for these vehicles as consumers are clearly less willing to pay for these types of cars. 

The confidence level in the above findings is high. The two regression models outlined in the earlier section gave the same results regarding which are the most important features. These results are also in line with the correlation matrix that was calculated in the early stage of the analysis. While local market conditions
may vary, the above results apply for used vehicles sales in the state of California and are based on a total of 6311 samples. 

![Summary abs value coefficients 111923a](https://github.com/fredrik-pettersson/Practical-Application-2/assets/146313002/2ffa7f03-d542-47b0-9d46-7d65c0e05505)

Figure above shows the top six features associated with used vehicle price: Year, engine size (cylinders), condition, diesel engine, and pickup truck are associated with higher price, while front wheel drive is associated with lower price. To a lesser degree, Lexus is associated with a higher price, while sedans are associated with a lower price. 
