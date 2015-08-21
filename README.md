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
cordova plugin add cordova-sqlite-storage
cordova emulate ios
```
