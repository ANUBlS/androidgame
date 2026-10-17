# Junction Control

A top-down traffic-light game for Android. Tap traffic lights to switch them between red and green and keep the town moving.

- 12 maps with curved roads, roundabouts, one-way streets, turn bans and random arrow lights; each map unlocks after clearing 5 levels on the previous one
- Levels and Endless modes, Light / Normal / Heavy / Rush hour traffic
- Clear, rain and snow weather (rain slows cars, snow makes them slide on ice)
- Pedestrians with walk signals on city maps, ambulances, buses, trucks, wrecks that block the road
- Day and night, 1× / 2× / 3× speed

## Install

Download `JunctionControl.apk` from the latest [release](../../releases/latest) and open it on your phone (allow "Install unknown apps" for your browser or file manager when asked).

## How it is built

The game is a single HTML5 canvas page (`app/src/main/assets/index.html`) wrapped in a full-screen Android WebView (`MainActivity.java`), so it runs offline. Every push to `main` builds a signed APK with GitHub Actions and publishes it as a release.
