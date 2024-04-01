---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1>Shattered Nights: Unveiling San Francisco's Driving Under the Influence Epidemic</h1>

Authors: Manos Loukaidis and Nico Sherpa

![Golden Gate Bridge](assets/golden_gate.jpg)

Almost every day, we can read about local crimes in the newspaper, and get so overwhelmed with the load of incidents, that it can be very hard to get the big picture of what is actually going on. On this page, we want to investigate and visualize the vehicle related criminality in San Francisco, by looking at the San Francisco Crime Dataset, that contains data from between 2003 and 2018.

<h2>Incidents are dependent on time</h2>

There are several factors that might have a significant influence on the occurance of intoxicated driving incidents in San Francisco. On of them is time. Considering the whole dataset and plotting the aggregated time series, we can observe that incidents occur more often at weekends, a bit lesser in the summer months, and especially closer to the night.

<iframe src="/assets/combined_crime_plots" width="100%" height="1000px"></iframe>

<h2>There are intoxicated-driving-hotspots</h2>

We can clearly observe from the map below that the majority of "Driving under the influence" incidents occur within the greater area of San Francisco where numerous nightclubs are situated. Additionally, the map highlights that many violations are concentrated along the highways, indicating a heightened likelihood of police presence and alcohol checkpoints targeting drivers departing from these nightclubs. This area likely serves as a hotspot for various illegal activities due to the significant presence of nightclubs.

<iframe src="/assets/map.html" width="100%" height="600px"></iframe>

Check out the [Nightclubs in San Francisco on Google Maps](https://www.google.com/maps/search/nightclubs+in+San+Francisco/@37.7550043,-122.4926137,12.53z/data=!4m2!2m1!6e1?entry=ttu), its quite interesting to see the overlap with our map from above.

<h2>What the hell is happening at 7pm?</h2>

To not overload the next graphic, we included incidents of driving under the influence only from 2015, and plotted them on the hour of the day. Interestingly, we can confirm the insights from the two previous plots, that during night the incident occurance increases, and that we can spot the focus area around the night clubs in San Francisco. 

<iframe src="/assets/Heatmap_with_time.html" width="100%" height="600px"></iframe>