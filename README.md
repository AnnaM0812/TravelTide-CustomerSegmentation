# TravelTide-CustomerSegmentation
Customer segmentation using SQL, Python, feature engineering, and machine learning for optimizing TravelTide's rewards program
##**Introduction**

To address growing competition and improve customer retention, travel company has launched a project aimed at creating loyalty perks for the clients. The objective is to identify the main factors that drive customer loyalty and develop perks that will enhance customer relationships, encourage repeat bookings, and elevate overall satisfaction. This report outlines the insights gained from data analysis, which included dividing the customer base into eight segments and offers practical recommendations.

##**Methodology**

The analysis included an in-depth examination of customer booking habits, survey feedback, and loyalty behavior. It was applied clustering methods to divide the customer base into eight unique segments, considering factors like booking frequency, travel preferences, spending behavior, and customer feedback.

##**Google Colab Notebook**
Access the Google Colab notebook for this project <a href="https://colab.research.google.com/drive/1DEQMf07xM2oRx_Ua50RPh1ztxMZr6yOr#scrollTo=36REOwN6CxwT">here</a>.

##**Key Findings**

We found eight groups that helps us understand our clients better, so as to assign specific perks that will be considered of value to them.

##**Recommendations**

Based on these findings, ich recommend the following steps:

1. Pilot Program for Key Segments: Implement a pilot loyalty program targeting the eight categorized groups with the assigned perk.
2. A/B Testing for Perk Effectiveness: Conduct A/B testing within each segment to measure the effectiveness of different perks.
3. Continuous Feedback Loop: Establish a mechanism for continuous feedback from customers on the loyalty perks offered.


####**A/B Testing to Evaluate Perk Effectiveness**####
***Objective***: Test the effectiveness of perks in increasing user engagement (e.g., booking rate, money spent, session duration) using A/B testing.

***Method***:

Split the customer base: Split each customer segment in half into two groups. One group receives a perk (e.g., free hotel night, flight discount), and the other group does not.
Testing period: Run the test over three months, tracking metrics such as:
Number of bookings (hotel, flights)б Average trip duration, Total money spent per customer, Cancellations and returns.

***Expected Insights:***

Which perks drive more engagement and bookings.
Which customer segments respond better to which perks (e.g., luxury travelers might prefer free hotel nights, while budget travelers may respond better to flight discounts).

***A/B Test Metric:***

Chi-squared test: This statistical test we can use to check whether the differences in booking behavior between those who received perks and those who didn’t are statistically significant.
Hypothesis: The group that receives perks will show higher engagement in terms of booking rate and money spent, especially among frequent travelers and high-spending customers.

####**Long-Term Strategy: Supervised Learning/Classification for Personalization**####

To build a more robust, future-proof recommendation system:

***Data Collection for Supervised Learning:***
Continuously gather more data on customer behavior, including the perks they respond to and their preferences. Use this data to train a machine learning model (e.g., classification models like logistic regression, decision trees, etc.).

***Classification Task:***
Predict which perk a customer is likely to respond to based on their previous behavior (e.g., past spend, number of flights and hotels booked, cancellations).
Goal: Build personalized marketing campaigns where perks are tailored to individual customer preferences.

***Ask Customers for Favorite Perk:***
Add a feedback loop where customers can directly state their favorite perks during or after a booking. This will further refine your perk-based marketing strategy by combining survey data with behavioral data.

