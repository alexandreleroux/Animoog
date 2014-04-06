The interactive map is here: https://github.com/alexandreleroux/Animoog/blob/master/map/animoog-map.geojson

Animoog Users Map - Instructions for Contributing
============================================

This map is for the <a href="http://animoog.org/map">Animoog Users Map - animoog.org/map</a>, everyone is welcomed to contribute to it.


Use cases
---------

* Find Animoog users and fans near you and meet to share tips and tricks, and maybe even jam together?
* Find Moog-related stores around you
* Maps are fun!


Adding yourself to the map
--------------------------

THIS IS CURRENTLY THE BLOCKER - we need a way for John Doe to easily add himself on the map without being too laborious for non-geeks

BACKGROUND
Map data, such as the location of Animoog users and fans around the world, can be stored in a GeoJSON file. This file format is automatically displayed over a map by GitHub [1]. While there's more and more ways to leverage geojson data on GitHub [2], it remains pretty difficult for most people to add data on a GitHub GeoJSON file and associated map.

References:
[1] https://help.github.com/articles/mapping-geojson-files-on-github
[2] http://gitspatial.com/


INSTRUCTIONS - (these need to be more detailed step-by-step instructions... coming...) - MISSING is screenshots for all of these steps...
* Login or register to GitHub
* Go to https://github.com/alexandreleroux/Animoog/blob/master/map/animoog-map.geojson
* Click on 'Fork' button top-right
* Click on the 'geojson.io' button top-right
* Add your location
* - instructions to come...
* Click 'save' icon
* - Enter a commit message such as 'Adding myself to the map'
* Click on the GitHub icon top-left to return to Github with your changes
* Click on 'map', to go back one level higher
* Click on the compare button on the left
* Click on 'Create Pull Request'

Bravo, you're done! Once I'll accept your pull request, the map (add link here) will be updated and all other users will see the improvements you've done.


Warning
-------

PRIVACY warning: 
* Please add only yourself and Moog-related stores 
* Don't use the precise location of your home, you are responsible for the location accuracy and your associated privacy

To do
-----

* Use different pushpins per type (ie a different pushpin for stores than for people, distinguish the types of Animoog users and fans by color, etc.) -- that's easy to do... GitHub supports marker -color and the Maki icons
