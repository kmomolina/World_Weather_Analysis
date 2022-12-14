# World Weather Analysis

## Overview
The purpose of this report was broken down into 3 different sections:
- First, retrieve weather data using OpenWeatherMap's API call. I needed to pull 2000 random coordinates all over the world and then define their locations as well as finding the weather conditions for them.

- Second was to create a customer Travel Destination Map. I had to create a search engine that would find all of the locations with the ideal temperature the user selects AND find accomodations for those places. A map with plots of these ideal locations will help the user see it clearly.

- Finally, I needed to create a Travel Itinerary Map. This map should help give the user directions to multiple travel destinations, as well as bring them back to where they began.

## Results

After randomly creating 2000 coordinates, the coordinates needed to be assiciated with cities. Since Earth is 70% water, this means that many coordinates would fall in the ocean. I filtered out the coordinates in the ocean, as well as found the nearest cities to the coordinates. This resulted in 700+ different cities.

The map worked well, and when the user would hover over a point in the map, it would give you the name of the city, the nearest hotel, and the weather conditions. for the directions, I selected 4 places in Mexico to plan the road trip:
- Lazaro Cardenas
- Acapulco
- Tecoanapa
- Puerto Escondido

The maps in github all worked according to plan. Please see the images that are named maps in the file so you may see the results.
