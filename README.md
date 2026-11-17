# Tacheo Topside for Windows

Official downloads of **Tacheo Topside**, the companion program for the Tacheo cave survey instrument (and CartoTable, its cave survey and cartography workspace).

## Download

Open **[Releases](https://github.com/p0sull02/tacheo-topside-releases/releases/latest)**, download the `Tacheo-Topside-<version>-Windows.zip` file, unzip it somewhere you can write to (for example Documents) and run `Tacheo Topside.exe`.

Once installed, Topside checks this page for newer versions by itself (Updates and Upgrades > Topside) and installs them with one click.

Mac users: Topside for Mac is still on the Google Drive download page.

## What is in this repository

Only the release downloads and two small text files Topside reads to find out whether a newer version is out:

- `latest.txt` - the newest released version
- `test.txt` - a build waiting for its hardware test (read only by the builder's PC)

The program's source code is not here.

## Licence

Copyright (C) 2026 Phillip M. Sullivan. All rights reserved. Please share the link to this page rather than the files themselves.

## Unit firmware (Topside 1.6.108 and newer)

`firmware.txt` lists the current Tacheo and SAP6 firmware packages in `firmware/`. Topside reads it when it starts and when a
unit is connected, downloads anything newer for that unit's build (size and MD5 checked), and offers it on a bar at the top of
the window. New firmware no longer needs a new Topside.

