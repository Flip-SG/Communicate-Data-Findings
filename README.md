# Exploration FordGo Bike
Udacity Data Analyst Nanodegree

## Dataset

This dataset consists of information regarding 2,5 Millions of bike trips during
the 2019 year in San Francisco. Some columns like start_time, duration_sec, user_type,
bike_id deserve a special attention in data analysis.
The dataset can be found in [here](https://s3.amazonaws.com/baywheels-data/index.html)
and the documentation is available [here](https://www.lyft.com/bikes/bay-wheels/system-data)



## Summary of Findings

During the exploration, I found that the two user types present different behavior in bike trips.
The Customer user type is a casual member in bicycle sharing system. He has a lower frequency in
bike trips, but with longer trips durations (22.55 minutes on average). The Customer user type has
more bike trips count in Friday and Saturday than other day in a week. December is the month with
more Customer trips. The Customer user type uses bike directed to entertainment and turism.
The Subscriber user type is a permanent member in bicycle sharing system. He shows a higher
frequency in bike trips, but with shorter trips duration (11.27 minutes on average). The Subscriber
user type has more bike trips recorded in Tuesday, Thursday and Wedesnday. March is the month with
more Subscriber trips. The Subscriber user type uses bicycles daily to go to work / school.
Although hour 8 and hour 17 have the peak daily usage for both user types, the longest trips
happen between hour 16 and hour 19 of the day.



## Key Insights for Presentation

For the presentation, I focus on show first the Distribution of a Bike Trip duration for each User
types. In this way the user behavior will be introduced. So, the count plot Customers Bike Trips vs
Subscribers Bike Trips show the different in counting trips. The counting bar plot Bike Trip per
Month vs User Type enter here to show the monthly usage. After that, the stripplot Trip Duration
vs Trip per Hour of the Day vs User Type will highlight the routine daily of use for each User Type.
Concluding the presentation with the heatmap Trip per Weekday vs Trip per Hour of the Day vs User
type, recaping the insights.
