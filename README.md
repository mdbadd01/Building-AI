<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->


# Project Title
ParkPal: AI for Smart Urban Bench Planning
Final project for the Building AI course


## Summary
ParkPal predicts optimal bench placement in urban green areas by using walking patterns, sunlight data, and rest likelihood. It helps city planners increase comfort for pedestrians and elderly residents.


## Background
Cities often place benches arbitrarily, without considering real walking behavior, shade, or need for rest. This results in overuse in some areas and neglect in others.

Motivations:
My own experience walking long city blocks with my elderly parent
An interest in low-cost AI for municipal planning
Applying AI to improve quality of life in subtle ways

Problems:
Randomized or legacy bench placement
Elderly or disabled persons lack predictable rest points
Planners lack feedback on usage


## How is it used?
City planners upload data:
GPS traces of pedestrians
Sunlight/shade maps (e.g., from LiDAR or open satellite data)
Demographics like elderly population density
The AI suggests optimal coordinates for new benches.

Users:
City planning departments
Urban accessibility organizations
Elderly advocacy groups

Use case:
Planning park benches in a new green corridor
Adjusting rest points based on real-world need rather than visual guesswork


## Data sources and AI methods
Data:
OpenStreetMap walking paths
GPS walk traces (synthetic or anonymized sets from fitness apps)
Sun position API (e.g., sunrise-sunset.org)
Bench placement feedback (volunteer annotations)

AI Methods:
Clustering to find foot traffic concentrations
Logistic regression or k-NN to score areas for rest likelihood
Linear optimization for placement (e.g., spacing between benches, avoidance of obstructions)


## Challenges
No universal “perfect” location for a bench
Quality of GPS data varies
Does not guarantee safety (e.g., benches under bridges)
Lacks real-time adaptation without sensor networks


## What next?
Could grow into a full urban accessibility AI toolkit, including:
Lighting suggestions
Shade vs sun heat modeling
Wheelchair path estimation
Restroom proximity predictions

Needed:
More labeled training data
Public-private partnerships with municipalities
A mobile app for feedback ("I wish there were a bench here") 


## Acknowledgments
Inspired by long walks with my father through poorly equipped parks
Based on open concepts in urban design
OpenStreetMap and SunCalc
