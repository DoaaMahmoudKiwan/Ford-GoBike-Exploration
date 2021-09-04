This project was part of the data analysis nanodegree program offered by Udacity.
# Ford GoBike 2018 Exploration
## by Doaa Mahmoud Kiwan

## Dataset

The data consists of information regarding 1,863,721 bike rides, including
duration, start_station_name, end_station_name, member_gender, user_type, start_time, end_time and other attributes. The dataset can be found in the [here]https://s3.amazonaws.com/fordgobike-data/index.html) as 12 csv files for each month, then they need to be concatenated.



## Summary of Findings

In the exploration, I found that there was a strong relationship between the
trip duration and the user gender and the user type. The data analysis show that there are more male riders, however, female riders make longer bike rides on average. Similarly, subscribers are significantly more than customers, however, higher percentage of customers are taking longer trips than subscribers. I also investegate the relationship between user age and the categorical features: percentage of younger females is higher than the percentage of younger males and others. The subscribers appear to be on average older than the customers. Finally, the age of bike riders doesn't appear to change with the day or the month at which the ride starts.

Although the day and month at which the trip starts are not part of my main features of interest, there is an interesting relationship between the duration of bike rides and the day and month at which the trips take palce. Despite the fact that there are more rides during the weekdays compared to the weekends, the trips that take place on the weekends are longer. For the month at which the rides take place, there are more rides and longer rides in warm months (May-Oct) than colder months (Nov-Apr).

## Key Insights for Presentation

For the presentation, I focus maily on the influence of the user gender, type and age on the trip duration.
I start by introducing the trip duration variable, distributions of user age, user gender and user type. After that comes the scatter plot to show the relationship between trip duration and user age.

Afterwards, I introduce the relationship between the trip duration and each of the categorical variables : user gender and user type.
I use the box plots of illustrate these relationships. Finally, I show how the trip duration and user age are related to user gender for different user types in two separate plots using clustered bar charts.
