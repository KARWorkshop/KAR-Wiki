# KAR Workshop Quick Install

The KAR Workshop Quick Install (KWQI | pronounced like Quickie, thanks Taco) is a file format that has been in use since KARphin V2.
It allows us to install various content types to the user's KARphin client. And know how to structure the data so we can load it.

## K4 and KWQI
KARphin 4 comes with a revised KWQI spec (version 4). This includes changes to support Deluxe, Ignition and Hoshi and Luna respectivly. And mods made based on them.

## KWQI file

This is the core file that defines a mod's data. Used for whole ISO mods not single machine packs or Hoshi/Luna single mods.

```
PackageName: String || stores the name of the mod
GameID: String || the unique game ID associated with the mod

FrameWork: Framework Enum || The framework this mod uses. Since Hoshi and Luna have drastic changes and thus a mod made with one. Has differant needs compared to the other.

ReleaseURL: String || The base release we use to get assets and content to install.
```