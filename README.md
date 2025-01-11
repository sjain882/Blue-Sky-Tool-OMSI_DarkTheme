# Blue Sky Tool

Blue Sky Tool is developed as an advanced version of OMSI Map Tools. Blue Sky allows users to scan for missing objects, splines, AI Vehicles, parked cars, humans and drivers.

## Fork modified from original:

- Original software credits: CDLBT ([github](https://github.com/cdlbt-co) / [website](https://cdlbt.co/))
- Fork modification credits: sjain882 ([github](https://github.com/sjain882))

## Changes: 

- Upgrade from .NET Framework 4.0 -> .NET 8.0
- Add automatic light/dark theme support
- Fix app not exiting on close
- Fix visual cut-off bug in main page counts
- Fix progress bar going under main window
- Add support for Ground Textures 

## Dark theme:

Auto detects light/dark theme based on Windows 10+ app mode setting.

Automatically changes light/dark theme while running.

**💖 Thanks to:**

- **[AngryCarrot789](https://github.com/AngryCarrot789)** for creating **[WPFDarkTheme](https://github.com/AngryCarrot789/WPFDarkTheme)** - simple & easy to use dark theme that respects default WPF controls

- **[DerekGooding](https://github.com/DerekGooding)** for **[updating](https://github.com/AngryCarrot789/WPFDarkTheme/pull/32)** **[WPFDarkTheme](https://github.com/DerekGooding/WPFDarkTheme)** to .NET 8

Preview:

<img src="https://raw.githubusercontent.com/sjain882/Blue-Sky-Tool-OMSI_DarkTheme/refs/heads/master/Previews/Empty.png?raw=true" width="100%" height="100%"/>

<img src="https://raw.githubusercontent.com/sjain882/Blue-Sky-Tool-OMSI_DarkTheme/refs/heads/master/Previews/MapLoaded.png?raw=true" width="100%" height="100%"/>

## Download

Download this dark theme version: https://github.com/sjain882/Blue-Sky-Tool-OMSI_DarkTheme/releases/latest

Download original program: [cdlbt.co/bluesky](https://cdlbt.co/bluesky/)

## How to scan for missing files

In the main screen, click on the `Open Map...` button. In the file selection screen, navigate to the mapfolder of choice and select the global.cfg file.

Blue Sky Tool will now start scanning for files required by the selected map. Please wait patiently.

After scanning, all of the essential information will show up in the main screen. You will be able to see the map name, description, preview picture, number of tiles, objects, splines, AI vehicles and humans.

**Having missing tiles missing usually means the map maker has disabled some tiles when releasing the map, which is almost never the reason why a map appears empty.**

If there are missing objects, splines, AI vehicles or humans missing, you can go to the corresponding tabs to see the list of missing files.

## How to use the logfile viewer

To use the logfile viewer, first click on the `Logfile` tab.

Then, click on the `Open log file...` button. In the file selection screen, navigate to your OMSI directory and select `logfile.txt`. If you have made a copy of your logfile and renamed the file or placed elsewhere, click on the dropdown box `OMSI Log File (logfile.txt)`, and select `All Files (*.*)`, then select your log file.

The tool will then scan the logfile and divide the entries to three sections - information, warnings, and errors.

## About this project

This program is written in C# with WPF using Visual Studio 2019. 

## License
[AGPL 3.0](https://choosealicense.com/licenses/agpl-3.0/ "AGPL 3.0 License")
