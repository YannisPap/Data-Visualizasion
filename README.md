# Summary

Data aquired by the United States Department of Transportation for the period June 2003 - February 2017, show that over one out of four flights is delayed across all NYC airports. More specifically:  

* **Newark Liberty International Airport (EWR)** has the highest delays percentage (29%) accross all the US airports.  
* **LaGuardia Airport (LGA)** comes second in national level with 27%.  
* **John F. Kennedy International Airport (JFK)** comes forth in national level with 24%.  

The reason most of the times is the National Aviation System (NAS). This means that most of the delays are due to a broad set of conditions, such as non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control. Other frequent reasons are Aircraft Arriving Late and Air Carrier Delay. You may notice that this is the top reason for the delays in all major US airports.

 
# Design

On the visualization I wanted to compare both the delays across different airports and also the delays variation over time. Thus I used both a BarChart for the first and a LineChart for the second.

# Feedback
## Feedback 1

**Feedback**  
>One thing I noticed, look at SAN airport, there is a green bar but there is 0% extreme weather delays. So either the data is not being calculated correctly, or the plot is not being drawn correctly? This is really a nitpick, because all of the extreme weather data is either 0% or 1%. Also it seems like security delays are 0% across the board, perhaps you can just remove it and add a footnote that there was none or it is such a small amount of the data that it is not worth having. Because it took me a few seconds to see that there was no security delay data, just a tiny slice of yellow at the very top of the bars. Or you could add a table to show those amounts. Again a nitpick... Overall great job! your plots look good and it works well. Good Job!

**Changes**  

The accuracy of the values in the tooltip increased to 2 decimals.


- include all feedback you received from others on your visualization from the first sketch to the final visualization
Resources - list any sources you consulted to create your visualization

https://github.com/PMSI-AlignAlytics/dimple/issues/43