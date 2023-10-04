# Driving Change: A Data-Driven Strategy for Minimizing Diesel Bans

## Project Idea

Diesel driving ban zones are static traffic control measures against exceeding air pollution threshholds - especially for particulate matter and NO2 emissions. However, these measures  are only reviewed once a year to determine their necessity and effectiveness. The question I would like to investigate is: Are static restrictions such as the german driving bans necessary at all, because many driving ban zones are usually accompanied by an increase in total emissions. This sounds totally counter-intuitive at first, but when important roads are closed, cars have to take detours, which can then lead to increased emissions. 

This can be seen particularly well in the example of Darmstadt. Darmstadt is located in the middle of the Rhine-Main area. As usual for metropolitan areas, there are many commuters who drive not only within but also from the surrounding areas to or through Darmstadt. Unfortunately, Darmstadt does not have a bypass that would provide a connection to the Odenwald district, for example. All traffic is directed through the Darmstadt city area. Thus, very high levels of air pollutants have been measured on the few, but very heavily polluted entrance and exit roads, which has led to the establishment of diesel ban zones. Now, motor vehicles sometimes have to take long detours in order to cross Darmstadt.

However, Darmstadt did not exceed the limit of 50 micrograms per cubic meter on a single day last year. In some cases, the fine dust pollution at the measuring points was far below the permitted limit. Therefore, the question arises: Is it necessary at all to issue a static driving ban and to guide road users on detours through the city? Wouldn't it be possible to investigate various factors influencing particulate matter pollution and, based on this, to forecast when driving bans are necessary?

Influencing factors are

1. a) the traffic volume. Generally speaking, the more vehicles on the road, the higher the emissions. This data can be accessed via maps - such as Google Maps - or via traffic data counts of the cities. Darmstadt Provides minute-by-minute data on the number of vehicles and detector occupancy rate for each intersection.
2. b) Weather. Relevant parameters such as wind direction, wind force, temperature or relative humidity can be obtained directly from measuring points in the city of Darmstadt. Additional information about precipitation can be obtained via weather APIs.
3. c) Agriculture. Darmstadt is surrounded by a lot of agriculture, which can also contribute to particulate matter pollution through field work. However, I see this factor as an optional parameter to investigate.

## Data Collection

For this project, I needed data from three different areas: Traffic, emissions and weather data. 

The city of Darmstadt provides access to its traffic data via a [platform](https://datenplattform.darmstadt.de/verkehr/apps/opendata/#/) for interested parties. These are minute-by-minute data for every intersection in the Darmstadt city area. With the amount of data needed, however, the use of the platform was very costly, so I thank the city of Darmstadt for exporting the data directly from the traffic computer and making it available to me. Many thanks!

The weather data as well as the emission data are provided [here](https://www.hlnug.de/messwerte/datenportal/tabelle/t/1/14/4) by the Hessian Ministry.
