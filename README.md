# Homelessness and Shelter Access in Santa Clara County

## Research Question

How does the geographic distribution of homelessness compare with the distribution of shelter services across cities in Santa Clara County?

## Project Overview

This project explores the relationship between homelessness and shelter availability across Santa Clara County, California.

The dashboard uses 2025 Point-in-Time (PIT) Count data to visualize the number of people experiencing homelessness in different cities and compares those counts with selected shelter locations.

The goal is to make it easier to see whether shelter resources appear to be located near cities with higher levels of homelessness.

## Interactive Map

The dashboard contains an interactive MapLibre GL JS map.

### Red Dots: Homelessness

Each red dot represents approximately 10 people experiencing homelessness based on the 2025 PIT Count.

For example:

- A city with about 100 people would display about 10 red dots.
- A city with about 500 people would display about 50 red dots.
- A city with about 6,500 people would display about 650 red dots.

The red dots have a fixed visual size when the user zooms in or out.

Clicking a red dot displays information about the city, including:

- Total PIT Count
- Unsheltered count
- Sheltered count

### Blue Dots: Shelter Locations

Blue dots represent selected documented shelters or interim housing facilities.

Clicking a blue dot displays:

- Shelter name
- Shelter type
- Address

## Important Limitation

The red dots do **not** show the actual locations of individual people experiencing homelessness.

The PIT Count data used in this project are available at the city level. Therefore, the red dots are distributed symbolically around each city to visualize the relative number of people counted there.

Each red dot represents approximately 10 people, but its exact position on the map should not be interpreted as the location of those individuals.

The shelter layer is also an initial dataset of selected documented facilities and may not include every homelessness service in Santa Clara County.

## Data Sources

### Homelessness Data

2025 Santa Clara County Point-in-Time (PIT) Count

The PIT Count provides city-level estimates of people experiencing homelessness, including sheltered and unsheltered populations.

### Shelter Data

Publicly available shelter information was collected from organizations including:

- LifeMoves
- Family Supportive Housing

## Technology

This dashboard was built using:

- HTML
- CSS
- JavaScript
- MapLibre GL JS
- GeoJSON
- Grayscale vector-tile basemap
- GitHub
- GitHub Pages

The grayscale basemap is used so that the research data remain visually prominent.

## Current Dashboard Features

- Interactive MapLibre map
- 2025 city-level PIT Count visualization
- One red dot for approximately every 10 people experiencing homelessness
- Selected shelter locations
- Clickable PIT Count information
- Clickable shelter information
- Map legend
- Grayscale basemap

## Future Development

Future versions of this project may include additional homelessness resources, such as:

- Additional shelters
- Temporary housing programs
- Safe parking programs
- Food assistance programs
- Health clinics

Future analysis could also compare the number of services available in each city with its PIT Count and explore whether some areas appear to have greater gaps between need and available resources.

## Dashboard

View the published dashboard here:

**PASTE YOUR GITHUB PAGES LINK HERE**

## GitHub Repository

View the project repository here:

(https://stevieee-here.github.io/homelessness-services/)

## Author

Steven Liu
