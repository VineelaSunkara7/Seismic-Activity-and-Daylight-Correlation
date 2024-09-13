
# Earthquakes and Celestial Events: Exploring Global Seismic Activity and Daily Light Patterns

### Introduction

Welcome to my project! Here, I explore the relationship between seismic activity and diurnal patterns using data from the USGS Earthquakes API and the Sunrise Sunset API. The goal is to uncover correlations or patterns between daytime, nighttime, and seismic events, providing insights for disaster preparedness and geophysical studies.

### Data Sources

#### USGS Earthquakes API <https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson>
I utilize the USGS Earthquakes API to gather real-time insights into global seismic activity. This API provides detailed information on earthquake events, including magnitude, location, and event timestamps.

#### Sunrise Sunset API <https://api.sunrisesunset.io/json?lat=38.907192&lng=-77.036873>
The Sunrise Sunset API offers daily updates on astronomical phenomena such as sunrise and sunset times. This data is crucial for understanding the diurnal patterns I am analyzing in relation to seismic events.

### Conclusion

This project reveals a moderate negative correlation between latitude and earthquake magnitude, indicating higher magnitudes closer to the equator. The uneven spatial distribution of earthquakes highlights the importance of geographic factors in seismic risk assessment. These insights contribute to a deeper understanding of Earth's geophysical processes and can inform disaster preparedness strategies.

# Poster with quarto

This project uses <https://github.com/quarto-ext/typst-templates/tree/main/poster>

### Starting from the poster customized

Install ``typst`` <https://github.com/typst/typst> which is used to generate the poster PDF.

Download the zip file, at <https://gist.githubusercontent.com/bellecp/15ef13ac3da5a064e1c21cf4ef03a7f8/raw/dc4a9f495d18e781df790164014f4dc3a20ed911/my_poster.zip>
(do not clone the repository of this gist as you will be missing some files in the _extensions folder. Download this zip and extract it in your laptop).

Extract this zip, open a command line in the my_poster director, and run

```
quarto render my_poster_24x18.qmd
```

The poster can be customized, for instance as we did in this repository, including
embedding output from ``.qmd`` quarto documents or ``.ipynb`` notebooks.

### Starting from scratch

You may also start from scratch. The documentation is at
<https://github.com/quarto-ext/typst-templates/tree/main/poster>.


Start by installing ``typst`` and then initiate a template poster  with

```
quarto use template quarto-ext/typst-templates/poster
```

