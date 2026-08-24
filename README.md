# OptiPath

OptiPath is an interactive web application that solves the **Travelling Salesman Problem (TSP)** and finds an optimal route through user-selected locations on a map. It supports up to 10 points and displays the route, total distance, and visiting order.

## Features

* Interactive map-based location selection
* Brute-force TSP optimization
* Real-world road route visualization
* Total distance and route order
* Responsive design for desktop and mobile

## Technologies

* HTML, CSS, JavaScript
* Leaflet.js
* Leaflet Routing Machine
* OpenStreetMap

## Usage

1. Open `optipath.html` in a browser.
2. Click on the map to add at least 3 locations.
3. Click **Find Optimal Route**.
4. View the optimized route and distance.

## Algorithm

OptiPath uses a **brute-force permutation approach** to evaluate possible routes and select the shortest closed loop.

**Time Complexity:** `O(n!)`

