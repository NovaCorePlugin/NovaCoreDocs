# NovaWild

## NovaWild

NovaWild is a wilderness teleportation plugin designed for servers that need more control than a standard random teleport command.

Instead of sending players to fully random coordinates, NovaWild allows teleportation through configured zones.

Each zone has its own center point, configurable range and custom name.

This makes NovaWild ideal for:

* custom maps
* structured survival servers
* curated progression servers
* Towny-style setups
* servers with strict world boundaries

### Main Features

* Zone-based teleportation
* Configurable zone names
* Configurable center coordinates
* Configurable teleport range
* Map boundary protection
* Safe land teleportation
* Cooldown system
* No dependencies

### How it works

Players use:

`/novawild tp`

The plugin shows the available zones in chat.

Then players choose one zone using:

`/novawild tp <zone>`

Example:

`/novawild tp north`

The player will be teleported to a safe land position inside the configured zone range while respecting the world boundaries set in the config.

### Planned Features

* internal GUI
* in-game zone setup commands
* more admin utilities

NovaWild is part of the NovaCore ecosystem.
