# Search-Algorithm

The given  data is (tubedata.csv) in CSV format with the London Tube map (which is not necessarily to be up-to-date and complete). 
Each row in the CSV file represents a Tube "step" and is in the following format:
[StartingStation], [EndingStation], [TubeLine], [AverageTimeTaken], [MainZone], [SecondaryZone]
where:
• StartingStation: a starting station
• EndingStation: a directly connected ending station
• TubeLine: the tube line connecting the stations above
• AverageTimeTaken: the average time, in minutes, taken between the named stations
• MainZone: the main zone of the starting station
• SecondaryZone: the secondary zone of the starting station, which is "0" if the station is in only
one zone. 
Note: to define the zone for the ending station use the main zone if the secondary zone is "0" otherwise use the secondary zone.
Refrence tube map is given in below link

https://content.tfl.gov.uk/large-print-tube-map.pdf

The code demonstrates the Implementation of DFS, BFS, and UCS to find routes from a starting station to a destination station. For a path found, the program  prints/displays meaningful information such as: path in stations, cost in average time, number of nodes expanded.
