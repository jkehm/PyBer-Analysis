# PyBer-Analysis
## Module 5 Challenge

### Overview
#### Purpose
V.Isualize has given Omar and I another assignment. This time we will create a summary DataFrame 
so that important statistics can be easily viewed side by side. Then, we'll use Pandas and 
Matplotlib to create a multi-line graph, and we can comapre weekly fares for each city type.
Then we'll submit a report summarizing this data to some decision-makers at PyBer.
#### Resources
* Python/Jupyter
* Matplotlib/Pandas
* city_data.csv/ride_data.csv

### Results
For this activity there were two main deliverables, both of which can be seen below.

![This is an Image](https://github.com/jkehm/PyBer-Analysis/blob/main/Analysis/Deliverable%201%20Table.png)
 
(Figure 1. ride-sharing summary DataFrame)
![This is also an Image](https://github.com/jkehm/PyBer-Analysis/blob/main/Analysis/PyBer_fare_summary.png)

(Figure 2. multiple-line chart of total fares for each city type)



It is rather clear from both resources, that the Urban city type is the best market in terms of the most value in $USD, and drivers and riders. 
Interestingly, the Rural and Suburban city types are more expensive for the riders, and offer more money for the driver on average. However, this could very well be skewed since the drives will most likely be longer (and thus more expensive) in rural areas, than an urban area. Another thing that stood out to me, is that the same general trend is observed in the graph for all city types.

### Summary
The main issue that I see with the differences in city types, is that the Urban city type is oversaturated with drivers. Even though the largest population of rides happen in the Urban cities, there are far too many drivers. Due to this competition, the price has been driven down. Which is great for the rider, but hurts the drivers in the Urban area. 

The opposite is happening in the rural areas. There are only a few drivers available, and they are better able to control the market. Becuase of this, the fare is high, which may keep riders from using this service in the rural areas. To combat this the CEO needs to do a better job regulating prices to keep both the riders and drivers happy.

To make sure that there are not shortages of drivers, previous years' data could be used to predict spikes in volume for certain weekends/weeks/months etc. 

  **3 fixes:**
* Shift drivers around so that the urban areas are not oversaturated
* Regulate pricing so that drivers and riders are paying/being paid fairly
* Observe data from previous years to build trends, and predict what days/months which city types may need more support
