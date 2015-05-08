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

Map data, such as the location of Animoog players and Moog dealers, can be stored in a GeoJSON file. This file format is [automatically displayed over a map by GitHub](https://help.github.com/articles/mapping-geojson-files-on-github).

Adding yourself to the file that contains the map data:

1. Register and login to [GitHub](http://github.com) - this step is necessary to avoid spam on the map
2. In a second browser tab, open the [geojson.io](http://geojson.io) website
3. Copy the [raw animoog-map.geojson](https://raw.githubusercontent.com/alexandreleroux/Animoog/master/map/animoog-map.geojson) content to the geojson.io website in its '</> JSON' tab
4. Click on the 'Table' tab to edit the map content using the 'Table' view:
  1. Add new members by searching for its location (the magnifying glass icon) and then clicking the pushpin to place the marker on the map
  2. Add corresponding text and links in the Table view
5. Go to the [animoog-map.geojson file](https://github.com/alexandreleroux/Animoog/blob/master/map/animoog-map.geojson) page and click 'Edit this file' (the little pen icon), copy your improved geojson from the '</> JSON' tab on geojson.io and copy this content to members-map.geojson on GitHub
6. Indicate what you added or changed in the 'Propose file change' box and click the 'Propose file change' button
7. On the 'Comparing changes' page that loaded, click on 'Create pull request'

Bravo, you're done! Once I'll accept your changes, the map will be updated and all other users will see the improvements you've done.


Warning
-------

PRIVACY warning: 
* Please add only yourself and Moog-related stores 
* Don't use the precise location of your home, you are responsible for the location accuracy and your associated privacy

To do
-----

* Use different pushpins per type (ie a different pushpin for stores than for people, distinguish the types of Animoog users and fans by color, etc.) -- that's easy to do... GitHub supports marker -color and the Maki icons
