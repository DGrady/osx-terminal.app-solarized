# solarized-for-terminal.app
Profiles for Mac OS X Terminal.app to provide Solarized color schemes

Based on [Solarized](http://ethanschoonover.com/solarized) ([Github](https://github.com/altercation/solarized)) by Ethan Schoonover.

These profiles are available at https://github.com/DGrady/solarized-for-terminal.app/

## Installation

Once you have a local copy of this repository, just double-click the `*.profile` files to import them into Terminal.app.

## Notes

- These profiles work under the assumption that Terminal.app's defaults are reasonable, and they do not set any options except for colors.

- The 16 ANSI colors slots are identical in both profiles, and are set according to the corresponding values from the `TERMCOL` column in the [official color table](http://ethanschoonover.com/solarized). The only color values that differ between the two profiles are

|            | Dark    | Light   |
|------------|---------|---------|
| Text       | base 0  | base 00 |
| Bold Text  | base 1  | base 01 |
| Selection  | base 02 | base 2  |
| Cursor     | base 01 | base 1  |
| Background | base 03 | base 3  |

- The purpose of this port is to provide a dead simple way to get Solarized colors in Terminal.app. Although the official Solarized repository includes profiles for Terminal.app, these appear to date from a time when Terminal.app didn't provide good ANSI color support and the installation instructions recommend installing SIMBL plugins and performing other esoteric gymnastics. This is no longer necessary. In addition, although there are several outstanding pull requests to update the Terminal.app profiles in the offical repository, my non-comprehensive survey indicated two potential problems: 1) some of these pull requests change the colors, 2) these pull requests don't make it simple enough - we just need two files, and here they are.
