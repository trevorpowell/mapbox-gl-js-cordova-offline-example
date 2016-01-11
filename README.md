# mapbox-gl-js-cordova-offline-example

## Prerequisites

```
npm install -g cordova ios-sim
```

## Run the example

Clone the repository, add platforms for iOS and Android, add the Cordova SQLite plugin, and run app on iOS emulator.

```
git clone https://github.com/trevorpowell/mapbox-gl-js-cordova-offline-example.git
cd mapbox-gl-js-cordova-offline-example
cordova platform add ios
cordova platform add android
cordova plugin add https://github.com/litehelpers/cordova-sqlite-storage.git#0.7.10
cordova emulate ios
```

## Notes on use

The main thing to note is in the map style object. The "source" attribute under "layers" and the source name under "sources" must correspond to the filename of the .mbtiles file ("naturalearth" in the example). The "source-layer" attribute under "layers" should correspond to the layer name in Mapbox Studio when exporting the .mbtiles file.
