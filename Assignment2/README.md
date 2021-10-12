# Assignment 2

## Description

This assignment involved the creation of 3 maps. The first depicts 311 complaints as a point layer, with different types of complaints categorized under different colors. The second counts the number of noise complaints in each Manhattan NTA and colors NTAs based on the number of complaints. The third introduces a [dataset](https://www.kaggle.com/somesnm/heatmap-of-pubs-and-bars-of-new-york-city/data?select=bar_locations.csv) I found of bars and their location in New York City, counts bars per Manhattan NTA, and compares this with a point layer of party related 311 noise complaints.

## Interpretation

1. Noise complaints turned out to be quite evenly distributed around Manhattan, with the only clear areas lacking complaints being those that are not heavily populated residential areas such as Roosevelt Island, Randall's Island, and Governor's Island. Within Manhattan, Some areas that were particularly dense with noise complaints were the Lower East Side, TriBeCa, and some areas of Upper Manhattan like Washington Heights and Inwood. Based on my understanding of the city, I believe this has to do with the density of restaurants, bars, and residential areas in these neighborhoods. Noise complaints aren't just the product of noisy people, but also neighbors who want peace and quiet. Areas that are less heavily populated, like Midtown and the Theatre District, saw fewer noise complaints.

2. Party noise complaints seem to be concentrated at the upper and lower ends of Manhattan, which also happens to be where most young people in Manhattan live. Perhaps a correlation can be drawn between average age in a neighborhood and party noise complaints. Construction noise tended to focus around a few small clusters, like the one in FiDi, Washington Heights, and peppered throughout Midtown. It can be assumed that these areas were active construction sites during the time the data was recorded. Ice Cream Truck noise complaints were fairly scattered, but mostly concentrated around the Upper West and Upper East sides. Noise complaints that didn't fall in any of these categories were concentrated in the Upper West Side and in Chelsea.

3. In my third map, I tried to test the hypothesis that party complaints concentrated around areas with lots of bars. In order to visualize this idea, I conducted a point count of bars located in each Manhattan NTA and created a map with graduated colors, juxtaposed underneath a point layer of party related noise complaints. As you would expect, the areas with significant party noise complaints (LES, Washington Heights, Inwood) were also areas with high numbers of bars in the area. We can observe a correlation at this extreme, but it should be noted that there were still a significant number of party related noise complaints in areas that didn't have high concentrations of bars like the UES and Harlem. It would seem that there isn't a clear case for correlation, but when comparing the graduated map of bars per NTA to the second map (Uncategorized noise complaints per NTA), there is some clear overlap. It can be said then, with some confidence, that the density of bars in an NTA corresponds with the number of noise complaints.

## Map 1

![alt text](https://github.com/sammylevin10/UDM/blob/main/Assignment2/FinalMaps/Categorized311Noise.png)

## Map 2

![alt text](https://github.com/sammylevin10/UDM/blob/main/Assignment2/FinalMaps/NoiseComplaintsPerNTA.png)

## Map 3

![alt text](https://github.com/sammylevin10/UDM/blob/main/Assignment2/FinalMaps/BarsAndPartyComplaints.png)
