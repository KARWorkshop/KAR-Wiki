# Game

`.game` files are KWQI files for full ROM/ISO mods. They define the ID and URL used for getting the modded content, gecko codes, and memory card for the game.

Game files are stored in the KWQI folder and are defined in JSON.
```
formatVer: String || version of the file format.

name: String || The name of the game, used to render in mod loader as well as checking the folder for injecting content.

desc: String || A short description of the game used in the mod loader.

gameID: String || The unique game ID associated with game.

baseReleaseURL: String || The URL for the release where we will search for content when searching.

Framework: Framework Enum || Stores which framework it is using. Igniton is based on Deluxe, and has a fork of Hoshi called Luna. It changes things. Do depending on what mod you use as a base, you get differant features.
```