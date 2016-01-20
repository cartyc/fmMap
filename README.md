# fmMap
Render a google map in a FileMaker webviewer

makeMap(address, type, h, w, zoom)

# Args

- address should be a JSON object containing lat, lng and other keys. ex {lat : x, lng: y, title: This is a point}
- Type should be road, sat, or terrain. This will select the google map type
- h, w are the height and width of the map. I just set this as 100% for both so that the map takes up the whole webview.
- zoom is for the maps zoom level.
