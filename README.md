# Requeirment description
- A simple python web app hosted on github with simple one html file 
- This web app is a location randomizer that will take randomly selected specfic location in specific area in the map
- This web app has 2 mode: 'radius' and 'grid' mode

## Radius mode
- In radius mode, user will input 2 parameters
    1. A coordinate of starting point in a format of latitude and longtitude pair obtained from goodle map.
    2. A radius in km from that starting point    
- The app will then randomly pick single location within the circle of that given radius iwth the starting point as a center

## Grid mode
- In radius mode, user will input 2 parameters
    1. A coordinate of upper left corner of a grid in a format of latitude and longtitude pair obtained from goodle map.
    2. A coordinate of lower right corner of a grid in a format of latitude and longtitude pair obtained from goodle map.
    
- The app will then randomly pick single location within the a rectangular grid that is defined by those 2 coordinates

## Assumption
- The app is intended to be used in small area, so we can assume that the map surface is locally 2D euclidean space not spherical surface. Convert radius in km to latitude and longtitude under this assumption. Same for square gird construction.
- Assume uniform distribution over all location under the area to be randomized

# UI requirement
- Simple web app with a drop down to select mode
- An input boxes for inputting parameters that is different between mode
- Output a single randomly selected coordinate (if possible output google map link to that latitude and longtitude)

# Tool url
[Location randomizer](https://nmekvipad.github.io/location-randomizer/) 
