# Ford GoBike Sharing Analysis

## Project Overview

This project is an Exploratory Data Analysis (EDA) of the Ford GoBike sharing trip data for January 2018. The primary goal is to uncover valuable insights into user behavior, trip patterns, and system usage. The findings from this analysis can be leveraged by the Ford GoBike program to optimize operations, enhance user experience, and inform strategic decision-making for future growth and service improvements.

## Project Objectives

* **Understand User Behavior:** Identify patterns in trip duration, frequency, and timing based on user demographics (user type, gender, age).
* **Optimize Operational Efficiency:** Analyze trip origins and destinations to identify high-demand stations and potential imbalances in bike distribution.
* **Enhance User Experience:** Uncover insights into user preferences and usage patterns that can inform service improvements and targeted offerings.
* **Inform Strategic Decision-Making:** Provide data-driven insights to support decisions related to pricing, station expansion, marketing efforts, and program development.

## Dataset

The dataset used for this analysis is `201801-fordgobike-tripdata.csv`, which contains trip information for the Ford GoBike program during January 2018. Key features include:

* Trip duration
* Start and end times
* Start and end station information
* Bike ID
* User type (Subscriber/Customer)
* Member gender and birth year
* Bike share for all trip indicator

## Libraries Used

* pandas
* numpy
* matplotlib.pyplot
* seaborn
* scikit-learn (for potential future modeling, though the current project is EDA)

## Data Wrangling

The data wrangling process involved the following steps:

* Converting date and time columns to datetime objects.
* Calculating trip duration in minutes.
* Converting categorical columns (`user_type`, `member_gender`) to category data type for memory optimization.
* Identifying and noting missing values in `member_birth_year` and `member_gender`.
* Checking for and confirming the absence of duplicate records.

## Exploratory Data Analysis (EDA)

The EDA involved creating various visualizations to understand the data and identify key patterns. Some of the charts generated include:

* **Histogram of Trip Duration:** Visualizing the distribution of trip lengths.
* **Bar Chart of User Type:** Showing the proportion of subscribers and customers.
* **Bar Chart of Gender Distribution:** Illustrating the gender breakdown of riders.
* **Bar Chart of "Bike Share for All" Trips:** Examining the usage of the program.
* **Line Chart of Trips Per Day:** Identifying daily trends in ridership.
* **Bar Chart of Trips by Hour of Day:** Revealing peak usage times.
* **Bar Chart of Trips by Day of Week:** Showing weekday vs. weekend usage.
* **Bar Chart of Trips by Rider Age Group:** Understanding the age demographics of users.
* **Box Plots of Trip Duration by User Type and Gender:** Comparing trip length distributions across different user segments.
* **Countplot of User Type Across Genders:** Showing the breakdown of user types within each gender.
* **Line Chart of Trips Per Hour by User Type:** Comparing hourly usage patterns of subscribers and customers.
* **Bar Charts of Top Start and End Stations:** Identifying the most popular stations.
* **Grouped Bar Chart of Program Usage by User Type:** Examining "Bike Share for All" adoption.
* **Facet Grid of Trips by Gender Across Weekdays:** Showing daily gender-based ridership patterns.
* **Violin Plot of Trip Duration Across User Type and Gender:** Providing a detailed view of duration distributions.
* **Line Chart of Average Trip Duration Over Time:** Identifying trends in average trip length.
* **Map Plot of Start Station Locations:** Visualizing the geographical distribution of start stations.
* **Pie Chart of User Type Distribution:** Showing the overall proportion of user types.
* **Correlation Heatmap and Pair Plot of Numerical Features:** Exploring relationships between numerical variables.

## Key Insights

The EDA revealed several key insights, including:

* Subscribers form the majority of the user base.
* Trip durations are generally short, with peaks during commute hours.
* Weekday ridership is higher than weekend ridership.
* Specific stations near transportation hubs are highly popular as both start and end points.
* "Bike Share for All" program adoption appears relatively low.
* Distinct usage patterns exist between subscribers and customers throughout the day.

## Solution to Business Objective

Based on the EDA findings, the following recommendations are suggested:

* Implement dynamic bike rebalancing based on peak hours and station popularity.
* Develop targeted marketing strategies for subscriber retention and customer conversion.
* Enhance the promotion and accessibility of the "Bike Share for All" program.
* Consider pricing strategies that reflect different usage patterns.
* Strategically plan station infrastructure based on high-demand areas.

## Conclusion

This EDA provides a comprehensive overview of the Ford GoBike trip data for January 2018. The identified patterns and insights offer valuable information for optimizing the bike-sharing program and enhancing the user experience. Further analysis and predictive modeling could build upon these findings to provide even more targeted recommendations.

#
