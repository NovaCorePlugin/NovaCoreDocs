# Config options

NovaWild is built around configurable wilderness zones.

### Main configurable options

#### Zone Names

Each zone can have a custom internal ID and display name.

Examples:

* north
* south
* east
* west

#### Zone Center Coordinates

Each zone uses a central coordinate defined in the config.

The plugin will calculate a random position around that point using the configured range.

#### Zone Range

You can configure how far from the center the player may be teleported.

This allows you to create:

* compact spawn areas
* large wilderness sectors
* custom exploration regions

#### Map Boundaries

You can define minimum and maximum map coordinates.

NovaWild will keep teleports inside the allowed playable area.

#### Safe Spawn Logic

The plugin avoids invalid spawns and places players on safe land instead of water.

#### Cooldown

A configurable cooldown prevents command abuse and repeated teleports.

### Future Improvements

Planned future updates include:

* in-game zone editing
* GUI selection
* easier admin setup
