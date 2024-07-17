# 5.1_assignment
Practical Application Assignment 5.1: Will the Customer Accept the Coupon?
Coffee Coupon Acceptance Analysis
Context
This project explores the factors that influence whether a driver accepts a coffee house coupon when it is delivered to their cell phone. The analysis utilizes various visualizations and statistical summaries to distinguish between customers who accepted the coupon versus those who did not.

Data Description
The dataset comes from the UCI Machine Learning repository, collected via a survey on Amazon Mechanical Turk. It includes attributes such as:

User Attributes: Gender, age, marital status, number of children, education, occupation, annual income, and frequency of visits to bars, takeaway food, coffee houses, and restaurants.
Contextual Attributes: Driving destination, location, weather, temperature, time, passenger.
Coupon Attributes: Time before expiration (2 hours or one day).
Data Preparation
Handling Missing Data:

Dropped the 'car' column due to a high percentage of missing values.
Imputed missing values in categorical columns with the mode.
Creating a Coffee Coupon Subset:

Filtered the dataset to focus on coffee house coupons.
Analysis and Visualizations
The following analyses were performed to identify characteristics of customers who accept coffee house coupons:

1. Age Distribution
Finding: Younger individuals (around 25-30 years old) are more likely to accept Coffee House coupons. The age distribution for both accepted and not accepted coupons is fairly similar.
2. Income Distribution
Finding: Higher income brackets ($75,000 - $99,999 and $100,000 or more) have a higher acceptance rate. Lower-income groups (<$12,500 and $12,500 - $24,999) also show significant coupon acceptance.
3. Frequency of Visits to Various Venues
Finding: Individuals who visit coffee houses, bars, and restaurants (both less than $20 and $20-$50) more frequently (1-3 times) are more likely to accept coupons. The acceptance rate drops for those who visit these venues very frequently (greater than 8 times).
4. User Attributes
Marital Status: Married partners and those with unmarried partners have higher coupon acceptance rates compared to singles and divorced individuals.
Number of Children: Individuals without children are slightly more likely to accept coupons than those with children.
Education Level: Acceptance rates are relatively consistent across different education levels, though some high school graduates have a higher acceptance rate.
Occupation: Acceptance rates vary widely by occupation. Those in 'Education' and 'Healthcare' are more likely to accept coupons, while those in 'Protective Service' and 'Legal' are less likely.
5. Contextual Attributes
Driving Destination: Individuals heading home have a higher acceptance rate compared to those going to work or with no urgent place to go.
Weather: Acceptance rates are slightly higher on sunny and rainy days compared to snowy days.
Temperature: Acceptance is higher at 80°F compared to lower temperatures.
Time: Coupons are more likely to be accepted in the morning (10AM) compared to other times of the day.
Passenger: Individuals driving alone or with friends are more likely to accept coupons compared to those with kids or partners.
Direction: Those driving in the same direction as the destination are slightly more likely to accept coupons.
Conclusion
This analysis identifies key attributes that influence the acceptance of coffee house coupons. Understanding these factors can help in designing targeted marketing strategies to increase coupon acceptance rates.

