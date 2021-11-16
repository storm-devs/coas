# Running City of Abandoned Ships with the latest Storm Engine

> Tested with the latest version of *Sea Dogs - City of Abandoned Ships* as sold by [gog.com](https://www.gog.com/game/sea_dogs_city_of_abandoned_ships)

Copy the files in this repository to your CoAS installation. Overwrite files as needed.

Use the provided `utf8encode.py` script to convert all the existing script and text files to UTF-8.

```
python utf8encode.py PROGRAM
python utf8encode.py RESSOURCE/INI
```

Copy the latest engine files built from the [Storm Engine](https://github.com/storm-devs/storm-engine/releases) repository:
* engine.exe
* fmod.dll
* resource/techniques/*
* resource/shared/*

Optional: Use the original `Config.exe` to configure the game settings.

Use `engine.exe` to start the game.

> Log files are now stored in `"Documents\My Games\Sea Dogs"`
