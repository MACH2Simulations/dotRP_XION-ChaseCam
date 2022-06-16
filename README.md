# dotRP XION-ChaseCam

This is based on https://github.com/zhivotnoya/XION-ChaseCam - thanks to them!

This is a free-to-use HTML/javascript based overlay for roleplay streamers.  It mimics the overlay of the AXON bodycam, but since most folks play in 3rd person, it's a ChaseCam.

## Screenshot(s)

> TODO

## How to use

### Source from the Web

> TODO github pages hosting

### Local Download

1. Download this repository (Code -> Download ZIP or click on the Releases on the Right)
2. Unzip somewhere you wish to store this (near OBS)
3. Add a "Browser Source" layer and point at the `top-right.html` file
4. See the next section on setting your parameters
5. Activate the layer

## How to configure your parameters

If you wish to edit the parameters for a local download, or do not wish to use the configurator above, you can set the parameters by hand

After the `top-right.html` filename in the path in your browser source, append:

```text
?player=YOURPLAYERNAME&agency=YOURAGENCYNAME&callsign=YOURCALLSIGN&tz=America/New_York
```

The parameters here:

* **player=** -- the player name (consider using an abbreviation)
* **agency=** -- the agency you are showing (eg Los Santos PD)
* **callsign=** -- your player's callsign abbreviation (3 characters typically)
* **tz=** -- timezone you wish to show in the box. America/New_York (Eastern time) is typical. see [the list](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones). It will try to guess your local one if you do not specify.
