# Leaflet Challenge

# Project Description 

## Create a map visualization of earthquake data.
- Select a dataset from "https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php"
- Pull the JSON data using the url to use in the map visualization.
- Create a map that plots all the earthquakes based on their latitude and longitude.
  - Create markers that show the magnitude of earthquakes by the marker size and depth of the   
  earthquake by color.
  - Include popups for each marker that show additional information about the earthquake.
- Create a legend for the map.

# Software and Files
- Leaflet CSS: "https://unpkg.com/leaflet@1.6.0/dist/leaflet.css"
- Leaflet JS: "https://unpkg.com/leaflet@1.6.0/dist/leaflet.js"
- D3 JS: "https://d3js.org/d3.v5.min.js"
- Open Street Map for the tile layer: "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png"
- JSON file for earthquake data: "https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson"

# Output/Analyses
- Created the map object. 
<img width="497" alt="Screenshot 2023-04-16 at 4 49 00 PM" src="https://user-images.githubusercontent.com/119909433/232344364-f74f7ab4-e57f-481b-95f5-3e378097fdf6.png">

- Added the tile layer. 
<img width="806" alt="Screenshot 2023-04-16 at 4 49 19 PM" src="https://user-images.githubusercontent.com/119909433/232344385-986928d3-1a90-46d2-bb99-b06cb39071c5.png">

- Got the GeoJson data. 
<img width="821" alt="Screenshot 2023-04-16 at 4 49 51 PM" src="https://user-images.githubusercontent.com/119909433/232344412-296b8e7b-59da-4edb-8827-3b7027404b39.png">

- Created a conditional function to select each color based on the depth of the earthquake. 
<img width="826" alt="Screenshot 2023-04-16 at 4 50 24 PM" src="https://user-images.githubusercontent.com/119909433/232344449-9aaf2ec6-614b-4de0-9a09-72a552b8c9a0.png">

- Styled each circlemarker. 
<img width="736" alt="Screenshot 2023-04-16 at 4 51 06 PM" src="https://user-images.githubusercontent.com/119909433/232344494-f341b58c-d115-4322-9087-674b63f4bd20.png">

- Created/plotted a circlemarker for each point. 
<img width="909" alt="Screenshot 2023-04-16 at 4 51 53 PM" src="https://user-images.githubusercontent.com/119909433/232344536-838a3b8d-cce7-4467-aea8-320aaca3f242.png">

- Created a popup for each marker with information about the location, magnitude, and depth. 
<img width="784" alt="Screenshot 2023-04-16 at 4 53 09 PM" src="https://user-images.githubusercontent.com/119909433/232344597-76e91058-6af3-43f5-804b-9d4534f3315e.png">

- Created a legend with colors and values corresponding to the earthquake depth and formatted the legend. 
<img width="853" alt="Screenshot 2023-04-16 at 4 53 38 PM" src="https://user-images.githubusercontent.com/119909433/232344639-ba8365d0-ad6d-41d0-b9b0-0f9cb6834c46.png">
<img width="820" alt="Screenshot 2023-04-16 at 4 53 55 PM" src="https://user-images.githubusercontent.com/119909433/232344660-4efd446d-c85e-41a0-a102-f44a7ca3f61e.png">

- Displayed the final map. 
<img width="779" alt="Screenshot 2023-04-16 at 5 09 33 PM" src="https://user-images.githubusercontent.com/119909433/232345358-b45ce880-efbc-42df-93cb-b3218ddad1f9.png">


### Note: Some of the code was developed with the help of my tutor and one block of code was developed based on code from my tutor/a reference from Google Groups ("https://groups.google.com/g/leaflet-js/c/jsuGLzD5VsQ?pli=1"). See the included JS file for details. 


# Author 
-Brittany Wright github:brittanynicole7
