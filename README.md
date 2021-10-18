   Overview of the analysis:
________________________

     Our aim is to build a summary dataframe that displays ride-sharing data by city types of Rural, Urban and Suburban. We'll make a multiple line graph that shows
 total weekly fares by city type after having all the relative data. To count or sum up the total number of drivers, rides, and fares by city type, we used the pandas
 library  Groupby() function along with the count() and sum () functions. We were able to compute our average fare per ride and driver after pulling this data and 
 assigning it to functions. We were able to format into a new data frame and re-format the columns once we got all of that information.The pivot() and resample 
functions were used in the second part of this exercise to build a multiple line graph that shows the total fares for each week by city type between January 
and April of 2019.

Information retrieved from the Data:
___________________________________
     
    1) Urban cities have more drivers and relative lowest average fare per ride.
    2) Rural cities have least drivers yet large average of fare per ride.
    3) Suburban cities are on the second number relative to count of drivers.
    4) Urban cities have most drivers, fares and rides relative to other cities.

  ![d1](https://user-images.githubusercontent.com/83256206/137813871-fffbce91-df76-4fdc-9e83-407fa8dc796f.jpeg)


Chart for total fare by city type:
_________________________________

![d2](https://user-images.githubusercontent.com/83256206/137814025-eb6ed534-c608-4812-b703-97d7cc58bee1.jpeg)


Summary:
_______

  Based on our data, we can predict what kind of fares will be demanded based on the city type the passenger would be riding in. Despite the fact that we did 
not visit every single city, we have a good idea of what fares will be like from week to week depending on city type, which is enough information to determine 
the rates that will be charged once we can categorise the sort of city the customer resides in. To summarise, a rural region will fetch a higher fee since there
 will be fewer employees in the area, the travel time and distance will most likely be longer, and the average fare per trip and driver will be the highest of 
all city kinds.

Recommendations:
_______________

    1) Place the drivers to operate in their own neighborhood.
    2) Increase in fare where the riders don't get enough fare relative to trip.
    3) There should be increment or decrement in fare on the bases of places and amount of rides on daily basis.

