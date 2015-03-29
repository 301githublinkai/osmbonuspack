# OSMBonusPack
osmdroid is a library to interact with OpenStreetMap data inside an Android application. It offers an almost full/free replacement to Android map objects: MapView, MapController, Overlays, etc.

This "OSMBonusPack" library complements osmdroid with (very) useful classes:

*  [Markers](https://github.com/MKergall/osmbonuspack/wiki/Tutorial_0) with nice and flexible "cartoon-bubbles",
*  [Routes and Directions](https://github.com/MKergall/osmbonuspack/wiki/Tutorial_1),
*  [Points of Interests](https://github.com/MKergall/osmbonuspack/wiki/Tutorial_2) (directory services),
*  [Marker Clustering](https://github.com/MKergall/osmbonuspack/wiki/Tutorial_3),
*  Polyline, [Polygon](https://github.com/MKergall/osmbonuspack/wiki/Tutorial_5) and [GroundOverlay](https://github.com/MKergall/osmbonuspack/wiki/Tutorial_5), similar to their Google Maps equivalents,
*  Support for [KML and GeoJSON](https://github.com/MKergall/osmbonuspack/wiki/Tutorial_4) content,
*  Geocoding and Reverse Geocoding,
*  Integrated Cache Management tools for off-line maps
*  and more...

Have a look to the [samples](https://github.com/MKergall/osmbonuspack/wiki/Home), and to the [features](https://github.com/MKergall/osmbonuspack/wiki/features).

The [OSMNavigator](https://github.com/MKergall/osmbonuspack/wiki/OSMNavigator) application demonstrates the use of these classes. This is a generic-purpose Map/Navigation tool, including a KML viewer and editor.

# Examples
Geocoding, route display, bubble on the destination with the address and an image

![Geocoding, route display and bubble](https://github.com/MKergall/osmbonuspack/wiki/images/osmnavigator_1_1.png)

Turn-by-turn instructions shown in bubbles (with instructions in the default language of the phone):

![Turn-by-turn instructions shown in bubbles](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_2_1.png)

The same turn-by-turn instructions shown in list view:

![Turn-by-turn instructions shown in list view](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_3_1.png)

Searching for fuel stations along the route:

![Searching for fuel stations along the route](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_4_1.png)

Searching fo cinemas inside an area, with clustered markers:

![Clustering](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_4_2.png)

Showing Wikipedia POIs related to the current map view. In the bubble, the "more info" button will open the full Wikipedia page: 

![Wikipedia POIs](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_5_3.png)

Showing geolocalized Flickr photos related to the current map view:

![Geolocalized Flickr photos](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_6_1.png)

Showing geolocalized Picasa photos related to the current map view: 1) on the map, and 2) as a list view

![Picasa photos on the map](https://github.com/MKergall/osmbonuspack/wiki/images/osmnavigator_7_1.png)

![Picasa photos as a list view](https://github.com/MKergall/osmbonuspack/wiki/images/osmnavigator_8_1.png)

When searching a place by name, shows its enclosing polygon

![Enclosing polygon](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_9_2.png)

MapBox Satellite maps in OSMNavigator:

![MapBox Satellite maps in OSMNavigator](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_10_1.png)

Support for KML content.

Google Maps "My Places"  | rendered with OSMBonusPack
------------- | -------------
![My Places](https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_12.png)  | <img src="https://github.com/MKergall/osmbonuspack/wiki/images/osmbonuspackdemo_11.png" height="398" />

# How to use it
Start with the [installation guide](https://github.com/MKergall/osmbonuspack/wiki/HowToInclude), then follow the [Tutorials](https://github.com/MKergall/osmbonuspack/wiki/Tutorial_0).

In the [releases](https://github.com/MKergall/osmbonuspack/releases), you will find the library (jar file), the javadoc, and the [OSMNavigator](https://github.com/MKergall/osmbonuspack/wiki/OSMNavigator) application.
