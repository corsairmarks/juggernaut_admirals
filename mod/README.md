# Overview

Summary

# Changes

Notes

## Compatibility

Notes

## Changelog

* 1.0.0 Initial version

## Source Code

Hosted on [GitHub]()

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.

TODO

interface/fleet_view.gui

container "fleet_view_shipyard_entry," children "leader" and "no_leader" seem to be what I need
CAN assign an admiral via event, but not visible in window.  Does add modifiers to Jugg
If all else fails, edict => event, event lets user pick which Jugg (since they can have the fed fleet/custodian ones too!), then which leader
With ordered things in 3.1, I can probably do by is_idle, then by level, descending