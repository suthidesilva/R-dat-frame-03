# R-dat-frame-03

## Scenario : Bike Sharing Data: Visualizing amounts

*Data description from Kaggle (https://www.kaggle.com/marklvl/bike-sharing-dataset).Bike sharing systems are a new generation of traditional bike rentals where the whole process
from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back to another position. Currently, there are about over 500 bike-sharing programs around the world which are composed of over 500 thousand bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.*

*Opposed to other transport services such as bus or subway, the duration of travel, departure and arrival position is explicitly recorded in these systems. This feature turns bike sharing system into a virtual sensor network that can be used for sensing mobility in the city. Hence, it is expected that most of important events in the city could be detected via monitoring these data.*

*This dataset contains the hourly and daily count of rental bikes between years 2011 and 2012 in Capital bikeshare system in Washington, DC with the corresponding weather and seasonal information.*

BikeShare.txt has the following fields

  - **instant**: record index
  - **dteday** : date
  - **season** : season (1:springer, 2:summer, 3:fall, 4:winter)
  - **yr** : year (0: 2011, 1:2012)
  - **mnth** : month ( 1 to 12)
  - **holiday** : weather day is holiday or not
  - **weekday** : day of the week
  - **workingday** : if day is neither weekend nor holiday is 1, otherwise is 0.
  + **weathersit**
    - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
    - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
  - **temp** : Normalized temperature in Celsius. The values are divided to 41 (max)
  - **atemp*** : Normalized feeling temperature in Celsius. The values are divided to 50 (max)
  - **hum** : Normalized humidity. The values are divided to 100 (max)
  - **windspeed** : Normalized wind speed. The values are divided to 67 (max)
  - **casual** : count of casual users
  - **registered** : count of registered users
  - **cnt** : count of total rental bikes including both casual and registered

**Create an RMarkdown where you use ggplot2 to create the visualizations specified below with "BikeShare.txt". For each graph listed below, include,**

  -If you create a new dataframe where averages are calculated, have RMarkdown display the averages you calculated. Regular R output will suffice!
  
  -The graph
  
  -A description of the graph that would serve as the caption. Describe the graph to the reader and tell them what you want them to notice when looking at the graph (essentially a caption).**

  -Put this directly below the graph in your RMarkdown
  
  -A brief description of your design choices, or if you think a different graph would be more appropriate.

