# Homelessness and Shelter Access in Santa Clara County

## Research Question

How does the geographic distribution of homelessness compare with the distribution of shelter services across cities in Santa Clara County?

## Project Description

This project explores the relationship between homelessness and shelter availability across Santa Clara County, California.

The interactive dashboard uses 2025 Point-in-Time (PIT) Count data to compare the number of people experiencing homelessness in different cities with the locations of selected shelters.

On the map:

- Each red dot represents approximately 10 people experiencing homelessness.
- Red dots are distributed symbolically within or around each city based on the city's PIT Count.
- Blue dots represent selected shelter locations.
- Users can click the map markers to view additional information.

The red dots do not represent the exact physical locations of individual people experiencing homelessness. They are a visualization of city-level PIT Count data.

## Data Visualization

### Homelessness

The dashboard uses 2025 city-level PIT Count data for Santa Clara County.

Each red dot represents approximately 10 people counted in the PIT Count.

For example, a city with approximately 500 people experiencing homelessness would display about 50 red dots.

### Shelter Locations

Blue markers represent selected homelessness shelters and interim housing locations.

Clicking a blue marker displays information such as:

- Shelter name
- Shelter type
- Address

## Data Sources

### Homelessness Data

2025 Santa Clara County Point-in-Time (PIT) Count

The PIT Count provides estimates of sheltered and unsheltered people experiencing homelessness across cities in Santa Clara County.

### Shelter Data

Shelter locations were collected from publicly available information, including:

- LifeMoves
- Family Supportive Housing

## Map Technology

The dashboard was built using:

- MapLibre GL JS
- A grayscale vector-tile basemap
- GeoJSON data layers
- HTML, CSS, and JavaScript
- GitHub Pages

The grayscale basemap helps keep the research data visually prominent.

## Important Limitation

The homelessness data are available at the city level.

Therefore, the red dots on the map should not be interpreted as the exact locations of individual people experiencing homelessness.

The dots are distributed symbolically to help visualize differences in homelessness counts between cities.

Similarly, the shelter locations included in the first version of the dashboard represent selected documented facilities and may not include every homelessness service available in Santa Clara County.

## Future Development

Future versions of the dashboard may include additional homelessness resources, such as:

- Food assistance programs
- Health clinics
- Safe parking programs
- Temporary housing programs
- Additional shelters

Future analysis may also compare the number and geographic distribution of services with homelessness levels in each city.

## Dashboard

View the interactive dashboard here:

(https://stevieee-here.github.io/homelessness-services/)
