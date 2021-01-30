# KTaNEManualTextures

This repository contains image files for every page of every manual of the [Repository of Manual Pages](https://ktane.timwi.de/).

`Manuals.json` is a list of all manuals that are contained within this repository. Properties:
- `ID:` The module/widget's ID
- `Name:` The name of the module/widget
- `Pages:` A list of all pages of the manual. They reference the images in the `Manuals` folder.
- `Modified:` The date and time that the pages of the manual were updated on this repository. This is used by the fetcher program to check whether or not a manual here is outdated so it can update it.