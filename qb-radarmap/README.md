# qb-radar
An interchangeable vehicle radar, made for [QBCore Framework](https://github.com/qbcore-framework); have the ability to switch between a square and circular radar, via config settings, inspired by [NoPixel](https://www.nopixel.net/). :green_heart:

Handcrafted by yours truly, [GlacielGaming](https://github.com/GlacielGaming) and [whelanmjoshua](https://github.com/whelanmjoshua) for [Eminence Studios](https://github.com/Eminence-Studios). Please do not redistribute without our express permission.

# Dependencies
* [qbcore framework](https://github.com/qbcore-framework) ❤️
* [qb-hud](https://github.com/qbcore-framework/qb-hud) - or any hud that properly hides components when exiting a player vehicle.

# Our Recommendations!
* [eminence-hud](https://github.com/whelanmjoshua/eminence-hud) - you're definitely going to want this hud, it goes perfect with our radar (minimap)

# Recommended Map Textures
* [dlk_maps_fivem](https://github.com/omgugly/dlk_maps_fivem) - if you're looking for better textures for how the radar and overall map looks!

![FiveM Maps](https://i.imgur.com/O4WFkHX.png)

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

## Manual

* Download the script and put it in the `[qb]` directory.
* Add the following code to your server.cfg/resouces.cfg
```
ensure qb-radar
```
### MAKE SURE YOU'RE NOT INSIDE A VEHICLE WHILE CHANGING RADAR TYPE OTHERWISE, THE OUTLINE BORDER WILL NOT LOAD CORRECTLY AND YOU'LL HAVE TO EXIT THE VEHICLE AND REENTER TO FIX IT! ###

# Configuration
### qb-radar/client.lua
```
EnableCircleMap = true
```

# Change Logs
### 0.0.1
* Initial release

# Issues and Suggestions
Please use the GitHub issues system to report issues or make suggestions, when making suggestion, please keep [Suggestion] in the title to make it clear that it is a suggestion.
