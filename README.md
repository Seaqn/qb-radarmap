# qb-radar
An interchangeable vehicle radar, made for [QBCore Framework](https://github.com/qbcore-framework); have the ability to switch between a square and circular radar, via config settings, inspired by [NoPixel](https://www.nopixel.net/). :green_heart:

# Dependencies
* [qbcore framework](https://github.com/qbcore-framework) ❤️
* [qb-hud](https://github.com/qbcore-framework/qb-hud) - or any hud that properly hides components when exiting a player vehicle.

# Features
* Live updates after configured between each radar type
* Outline borders included with each radar type
* Outline border color customizable
* All icons, locations makers, and GPS markers are kept contained within radar types
* Moveable and resizeable positions for each radar located inside client.lua
* Square radar 🟦
* Circle radar 🔵

# Preview
![qb-radar preview](https://i.imgur.com/puhIcBf.png)

https://user-images.githubusercontent.com/52267651/130535872-548be4c5-3165-49dd-bac3-d290d05820c1.mp4

# Installation

* Download the script and put it in the `[qb]` directory.
* Add the following code to your server.cfg/resouces.cfg
```
ensure qb-radar
```

# Configuration
### qb-radar/client.lua
```
EnableCircleMap = true
```

# Warning
### MAKE SURE YOU'RE NOT INSIDE A VEHICLE WHILE CHANGING RADAR TYPE OTHERWISE, THE OUTLINE BORDER WILL NOT LOAD CORRECTLY AND YOU'LL HAVE TO EXIT THE VEHICLE AND REENTER TO FIX IT! ###
