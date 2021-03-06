---
title: Navigate the Mars Rover (The Mars Colonization Program)
summary: Microsoft Engage Mentorship Program 
tags:
- Path Planning
date: "2020-06-03T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: 
  focal_point: Smart

links:
- icon: linkedin
  icon_pack: fab
  name: Follow
  url: https://linkedin
- icon: 
  icon_pack: fab
  name: Visualizer
  url: "https://jaihonikhil.github.io/THE-MARS-COLONIZATION-PROGRAM/#"
url_code: "https://github.com/jaihonikhil/THE-MARS-COLONIZATION-PROGRAM"
url_pdf: ""
url_slides: ""
url_video: 
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
This was a project/ competition offered by Microsoft India to the selected students as a part of the Engage Mentorship Program.

This project required to implement and innovate the Pathfinding Library. As a result, We implemented a new heuristics added to our pathfinding visualizer by the name of Optimized Manhatten. Having tested the heuristic on benchmark, we have managed time reduction by approx 50% in case of Astar algorithm and approx 15% reduction in time in Best First Search. 

The length of path and number of operations remain unaltered, hence we have not applied greedy algorithm to reduce time and compromise on the optimal path. We have also added an option of speed in the naivigation bar, the speed with which the rover reaches the space station can be managed.

**Gateway Heuristic**

The maze and patterns present in the repository were added to test a new heuristic called the Gateway heuristic. The gateway heuristic pre-calculates the distances between entrances/exits of the areas. It also proceeds in two phases. Preprocessing Phase: The map is decomposed into areas in an identical way as for the dead-end heuristic.

 We define the boundaries between areas as gateways (or gates). A gateway can be of an arbitrary size, but an artifact of our decomposition algorithm is that its orientation is always either horizontal or vertical. Next we use multiple A* searches to pre-calculate the (static) distance between gates. For each gateway we calculate the path distance to all the other gateways (cost of infinity if no path exists). Alternatively, one could calculate only the distances between gateways within each room and then use a small search to accumulate the total cost during run-time. However, our approach results in more accurate heuristic estimates and faster run-time access.
