# Accessibility Scoring

This is a mini-project created to score the accessibility/walkability of nearby places such as hospitals, police stations, etc. in an an area which is determined by supplied geospatial coordinates.

# Scoring Formula

![latex_formula_img](https://lh3.googleusercontent.com/pw/ACtC-3f9uL-n3s98LD2OFJH3pbpCvSn9jWAgfA0aloIGIGw6wlGwbjnP0SlajJ7UJJFT_6PVQhlBdM8UkTYecFHfosW7rLG5R6EEpZprClCGnOmdxXCcvsXxxadmIRbmzm7vsus5ghx4wb7k8llvSQbjfMNsTg=w1093-h202-no?authuser=0)
where: 
x = value or a set of values containing the distance to the nearest facility 
C = normalizing constant

## Getting started

 1. Install the required libraries and import them.
 2. Change `filepath` accordingly.
 3. Get the bounding box of the location area. You may use this [tool](https://boundingbox.klokantech.com/) to speed up the process.
 4. Determine which place category/amenity you want. Choose from the [list of amenities](https://wiki.openstreetmap.org/wiki/Key:amenity) supported by OpenStreetMap.  
 5. Provide the considered maximum distance in meters. (Ex. 500 means everything within the 500m range will only be considered)

## Required libraries

All of the codes are built on the Python programming language. This includes the libraries used too. 

Full list of libraries used are indicated in the jupyter notebook.

