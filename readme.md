# Ford GoBike System Data Exploration
## by Mohammed Alkhrashi


## Dataset

Ford GoBike is a public bicycle sharing system in the San Francisco bay area, it's the first regional and large-scale bicycle sharing system deployed in California. it has over 2600 bicycles in over 250 stations.

This dataset contains over 500,000+ bike trips recorded.

Data variable description: https://www.lyft.com/bikes/bay-wheels/system-data
Download the data: https://s3.amazonaws.com/baywheels-data/index.html


## Summary of Findings

-Most bike trips start and end at 8AM or 5PM which aligns with a typical workday of 9AM-5PM.

-Trip duration average with good sample size peaks at 2PM with an average of ~15 minutes, at 3AM it also peaks with an average of ~18 minutes but notice that the sample size of data before 6AM is relatively low since not many people use bikes at the time.

-Non-subscribers have on average longer trip duration than subscribers

-Females have longer trip duration then males in everyday of the week and at every hour.

- Weekends have on average longer trip durations (~15 minutes) than workdays average duration(~11 minutes), that's mainly coming from the non-subscribers; as subscribers have a consistent trip duration throughout the week.

-Subscribers ride count falls in the weekends, while non-subscribers ride count rise in the weekends, could be because subscribers use it mainly to go to work.

In conclusion trip duration is affected by some features, mainly: Gender, User type (Subscriber or not), Day of the week, Hour of the day.

## Key Insights for Presentation

I will use my main feature of interesting for my presentation ( Trip duration), I will show various features that impact the trip duration in a slide, and I will give some notes about every plot.

I changed some labels in the presentation plots to make it clearer, for instance: Labeling "Day of the Week" instead of "day".
In one multivariate box plot that represented gender ,user type with trip duration.

Main insights:
1-Trip duration on workdays are shorter than Trip duration on weekends on average
2-non_subscribers Trip duration are longer than subscribers trip duration on average
3-Females trip durations are longer than males trip duration on average
4-The peak of trip duration on a day is at 2PM and 3AM but trip durations at 3AM are skewed due to low number of trips at that time
