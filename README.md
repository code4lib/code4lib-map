# code4lib-map

This is the start of the code4lib map, inspired by the [critlib map](https://www.google.com/maps/d/u/0/viewer?mid=15ASavNCIktR-ZaXHYEVOBNgKDJg&ll=34.05038383405213%2C-26.443405158593805&z=2).

[To view the map, open the map.json file.](https://github.com/code4lib/code4lib-map/blob/master/map.json)

## Getting Started

Add yourself to this map!

### Option 1

* Just edit the json file directly! The repo will automatically be forked! You can add any additional attributes that you like.
* Create a pull request back to origin code4lib-map
* Remember your privacy! Make sure your location is a public building or otherwise not personally accurate.

### Option 2

* Fork the repo
* Go to [geojson.io](http://geojson.io/)
* Open from github your forked repo of code4lib-map, authorize your organization
* Find your location add a point
* Go to table view, fill in data in the new row
* Save it directly from geojson.io to your forked code4lib-map github repo
* Create a pull request back to origin code4lib-map

### Option 3

* Create a github issues with your name, institution (if applicable), geocoordinates, and social media links you want included on the map (github/twitter/etc).

## Styling Conventions (optional)

**code4lib regional group**
marker-size: "large"
marker-symbol: "library"


Here are some more things you can do with this map:

- More about GeoJSON on Github https://help.github.com/articles/mapping-geojson-files-on-github/
- Embed the map using ```<script src="https://embed.github.com/view/geojson/code4libtoronto/code4lib-map/master/map.json?height=500&width=1000"></script>```
- Check out the simplespec: https://github.com/mapbox/simplestyle-spec

## Privacy

You may add information regarding yourself or your institution, but should not add information regarding other people without their express permission.

Please also be aware that the history of changes to the data file is retained indefinitely and that there may be limited tools available for removing unwanted entries in a permanent fashion.

## Troubleshooting

**My coordinates are off!**

Did you get your coordinates from Google Maps or OpenStreetMap? This map is going by OpenStreetMap data, so if you used Google Maps to get your coordinates, the lat/long might be off. Fix: Go to OpenStreetMap to get your coordinates.


