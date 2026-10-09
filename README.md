# Dusk

Public downloads for Dusk. Source is maintained separately in a private repository.

Download [Dusk.zip from the latest release](https://github.com/duskywusky/duskcs2/releases/latest/download/Dusk.zip), extract both applications together, and open `dusk-loader.exe`. Open CS2 before clicking **Load**.

Loading stays inside the loader, with its animation visible for at least three seconds. Press **Insert** in-game to show the menu; **End** unloads Dusk by default.

The new loader checks for external updates when opened and downloads them automatically. It verifies the release version and SHA256 checksum before replacing `dusk.exe`, preserves profiles, and retains an existing copy if the update fails.

Users with an older loader need to install this updater-capable loader once. Future external releases then update automatically. Loader UI changes still require replacing `dusk-loader.exe`.

Keep both EXEs together. Diagnostics are saved in `dusk.log` beside them. Release assets include both EXEs, the ZIP bundle, `version.txt` and `SHA256SUMS.txt`.
