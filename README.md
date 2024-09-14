# Hospital_Accessibility_R5R

### Research Question
What is the relationship between socio-economic, demographic determinants and the accessibility of essential healthcare services in Leeds and how can public transportation be modified to enhance accessibility for vulnerable populations?

### Objectives
- Analyse the relationship between journey times and population distribution by using a travel time matrix to assess the travel times to Leeds Central Railway Station.
- Assess the accessibility of Leeds’s parks, schools, supermarkets, and hospitals using hex grid by walk and transit.
- Examine how socioeconomic variables, including age, the number of children, and the status of dis- abilities, affect accessibility to hospital by using accessibility analysis. In particular, note any negative connections that would suggest restricted access for vulnerable populations.
- By Geographic Weighted Regression (GWR), measure the regional differences in the influence of so- cioeconomic and demographic factors on healthcare accessibility.
- To statistically validate the degree of accessibility inequality among the elderly, the disabled, and households with children, calculate the Gini coefficients.
- To help visualise spatial disparities, use the Getis-Ord Gi* statistic to spatially locate places with significantly high or low accessibility to healthcare services.
- Modified GTFS data to simulate improved bus service frequency and evaluate the possible changes in healthcare access coverage.

### Result

This study analyses the accessibility of urban healthcare via public transport in Leeds using a variety of detailed data sources, such as OSM network data, GTFS data, and socioeconomic variables from the UK Census. Notable strengths include the utilisation of the r5r software for in-depth accessibility analysis, Gini coefficient for estimating inequality and Getis-Ord Gi* statistics to investigate geographical variances. This method enables a more detailed understanding of the ways in which poor people’ access to healthcare is impacted by transport accessibility. Furthermore, the transformation of GTFS data to model increased bus service frequency offers useful perspectives on how transit changes could improve healthcare accessibility.

The accuracy of the project may be impacted by the fact that the key data sources, in particular the GTFS data, might not always be updated. This could lead to doubts regarding the real availability and timetables of transit choices. Further restrictions include the r5r package’s high processing requirements and the dependence on OSM data, which is not always reliable or complete. The study may not have captured changing daily or seasonal transit conditions due to its assumptions regarding bus frequency and the constant parameters utilised in accessibility analysis. Furthermore, concentrating just on particular demographic characteristics while ignoring more general health-related problems may limit our comprehension of other significant accessibility implications.

Furthermore, using advanced models based on machine learning instead of the static ones utilised in this study may be able to predict changes in healthcare accessibility and transit usage more dynamically, allowing for better adaptation to either brief disruptions or long-term changes in transport networks.Using real-time transit data, which shows actual bus frequencies and timings rather than those that are scheduled, is an additional option. Real-time data acquisition and processing, however, can be far more difficult and resource- intensive.

### Policy Suggestions

#### Targeted Improvement of Transit Services: 
Prioritise public transport service upgrades in underserved regions that have been identified as coldspots for low accessibility based on the Getis-Ord Gi* analysis. This may involve adding new routes that link these communities directly to important healthcare facilities or increasing bus frequencies, particularly during times when healthcare access is at its highest.

#### Expand Multi-modal Transport Options: 
Provide and encourage multi-modal transportation options that include public transportation, cycling, and walking. This might involve making it safer and easier for locals to get healthcare services without a car by enhancing bike lanes and pedestrian pathways that connect to important bus lines or medical facilities.

#### Enhance Transit Data Transparency and Regularity: 
Encourage regional transit authorities and organizations to keep up-to-date GTFS information. This reduces differences between reported and actual transit availability by ensuring the data reflects current transit schedules and routes. Furthermore, setting up public portals with real-time transit updates can help citizens and decision-makers make informed choices.

