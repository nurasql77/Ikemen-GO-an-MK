# MK Trilogy HD game assets

Put the game files in this folder, preserving the directory structure expected by Ikemen GO.

Examples:
- `assets/data/system.def` becomes `data/system.def` inside the APK
- `assets/chars/` files become `chars/`
- `assets/stages/` files become `stages/`

Files here are copied over the stock Ikemen screenpack when the Android APK is built. The build workflow adds them to the APK's asset manifest automatically. Do not put the outer `assets/` directory itself inside this folder, and do not add `manifest.txt` or this README to the game assets.

Important:
- Keep file and folder names exactly as the game expects.
- The Android asset manifest is whitespace-delimited, so avoid spaces in relative file paths.
- Only upload game files you are allowed to distribute. If you do not have redistribution permission, keep this repository private and do not publish the resulting APK.
- This folder currently contains no game data; the APK can build, but it will not be an MK Trilogy HD port until you add the required game files.
