# R Data Analysis and Visualization

This project is developed as a part of a lab course at Fraunhofer IAIS and RWTH Aachen. The main question risen was what if we could share cab rides?

## New Usage Concepts of Transport Data

Using data from [DIDI](https://www.didiglobal.com/) (Uber alike in China) and [NY yellow cabs](https://www.nycyellowcabtaxi.com/), I did come with an interesting solution on how we could reduce the CO2 emissions, while sharing rides. Chronologically the Project was developed as follows:

### First Presentation

Visualizing the NYC yellow cab data by first contouring the New York City using GeoJSON data.

![GeoJSON NYC](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS1_1.png)

Visualizing the clusters of requests through time of passengers calling a cab.

![Cab Request Cluster](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS1_2.png)

Visualizing cab fares and their trajectories.

![Cab Fares NYC](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS1_3.png)


### Second Presentation

Visualizing all the NYC yellow cabs companies, availability at a specific time of the day.

![NYC Yellow Cab availibility](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS2_1.png)

![NYC Yellow Cab availibility 2](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS2_2.png)


### Third Presentation

Visualizing a more detailed trip visualization. Each trip now has a different color, with a well-defined start and finish.

![New Trips](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS3_1.png)

I do show as well how many passengers are waiting for a cab in a time period of 3 minutes at geolocation. What we see is that in peak times there is more than one person waiting for a cab.

![New Trips 2](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS3_2.png)

![New Trips 3](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS3_3.png)

### Fourth Presentation

At this time a new data set is available for us to analyze, the DIDI (Uber alike) data are available.

![DIDI Trips](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS4_1.png)

It is interesting to see that we have a lot more data in the peak times using this data set, and how well the tool manages to visualize all the individual trips.

![DIDI Trips 2](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS4_2.png)

### Final Presentation

The final Presentation will answer the main question, is it possible for us to share cabs, and if so what are the benefits.

![Taxi Sharing Benefits](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS5_1.png)

I did analyse 5 days (although the trend was similar), and as we see from the picture below there are many similar trips that users could share a cab if they wanted. In theory that would save them money and as well cause less pollution to the environment.

![GPS Data Analysis](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS5_2.png)

We can now analyze the data coming from each trip on a selected time.

![GPS Data Analysis](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS5_3.png)

Let's see it in action by clicking at one of the starts of a cab trip. With red is the actual path the cab took, while in blue we have the Google API giving us the best route. Both are very similar for the case in the example above. We can as well see the speed of the cab at different parts of the road, as well as the LOWESS speed.

![GPS Data Analysis 2](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS5_4.png)

Here we have another example where the driver of the cab chooses a longer path to reach its destination. I did not have traffic data at that time in China, thus we cannot say what was the reason the driver took a longer path.

### Why not use busses? 

At peak times there were areas that many people traveled from and to at the same time. If we now analyze these paths, and if they used another means of transport such as busses we would have the following results.

![GPS Data Analysis 2](https://github.com/AldoMyrtaj/lab_project/blob/master/Demo/VIS5_5.png)

It is really interesting to see how could we all save the planet by using busses instead of cabs, this based on real world data analysis.





