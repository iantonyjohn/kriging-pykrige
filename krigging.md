The purpose of the code is to peroform krigging operation on a given shapefile with the given set of coordinate points containing nutrient information regarding soil in the particular coordinates.

One needs to just follow along the notebook to get perform the krigging operation
"data.csv" is the file containing the data which has the following columns, that are important for the code to work - latitude,longitude,nutrient; nutrient is the nitrogen content of the soil in kg/ha

One can find more details on ordinary krigging here-
    https://webcam.srs.fs.usda.gov/impacts/ozone/spatial/kriging.shtml
    https://pro.arcgis.com/en/pro-app/latest/help/analysis/geostatistical-analyst/understanding-ordinary-kriging.htm#:~:text=Ordinary%20kriging%20assumes%20the%20model,reasons%20to%20reject%20this%20assumption.
    https://geostat-framework.readthedocs.io/projects/pykrige/en/stable/contents.html

In this code the pykrige package is used to conduct interpolation along with the folium maps to generate the maps.

The shapefile called "region" is the shapefile of the place called Pathanamthitta of Kerala state of the country India.

The resultant of the code is the file named "krigging_result.html", which must be opened using the web browser for visualization of te results.

