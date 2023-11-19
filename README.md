# Practical-Application-2
What drives the price of a used car?  The goal is to analyze a dataset with information on 426,000 used cars to understand what factors make a car more or less expensive. The analysis provides clear recommendations to my client - a used car dealership - as to what consumers value in a used car.
# Data
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the driver whether he or she will accept the coupon. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

# Summary: Key Findings and Recommendations for Next Steps
Bar Coupon Acceptance
The bar coupon acceptance rate increases strongly with high bar attendance; drivers who go to the bar 4-8 times or more per month have a very high acceptance rate of 77%. Also, drivers who go to the bar at least once a month generally have high acceptance rates of 70% or more, provided that they are less than 30 years old, or have passengers who are not kids. Drivers who often attend bars seem rather price-sensitive since they make sure to use their coupons.

Next step should be to investigate what factors could encourage people who never, or rarely, go to the bar, by analyzing the people in these categories who did accept their bar coupons. For example, the graphs below suggest that among those who never or rarely attend bars, there are sub-segments such as the $100k+ income group that show relatively high coupon acceptance, and which could be targeted e.g. during sunny weather to maximize bar coupon acceptance rates and grow new customer segments:

