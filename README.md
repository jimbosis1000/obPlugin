# Obsidian Bulk Rename Plugin
[![](https://github.com/OlegLustenko/obsidian-bulk-rename/actions/workflows/CI.yml/badge.svg)](https://github.com/OlegLustenko/obsidian-bulk-rename/actions/workflows/CI.yml)
[![Release Obsidian plugin](https://github.com/OlegLustenko/obsidian-bulk-rename/actions/workflows/release.yml/badge.svg)](https://github.com/OlegLustenko/obsidian-bulk-rename/actions/workflows/release.yml)
[![GitHub license](https://img.shields.io/github/license/OlegLustenko/obsidian-bulk-rename)](https://https://github.com/OlegLustenko/obsidian-bulk-rename/master/LICENSE)
[![Github all releases](https://img.shields.io/github/downloads/OlegLustenko/obsidian-bulk-rename/total.svg)](https://github.com/OlegLustenko/obsidian-bulk-rename/releases/)
[![GitLab latest release](https://badgen.net/github/release/OlegLustenko/obsidian-bulk-rename/)](https://github.com/OlegLustenko/obsidian-bulk-rename/releases)
## Introduction
Now you can rename a bunch of files from the directory and all references also will be updated across the vault.

![](documentation/assets/Animation.gif)

> Under the hood this plugin is using obsidian API for renaming, but we just applying it for many files

# Features

> Whenever we're updating **Replacement Symbols** you can set new _Directory Location_ too
> so, you can also move files to _another directory_


## Rename/Move files based on folder location
Click _Search By Folder_

Update **Folder Location** where are you wanting to get files from, put **Existing Characters** from the file path
later on update **Replacement Symbols** those symbols will be used for in a new path.


## Rename/Move files based on tags
Click _Search By Tags_

Put tags in **Tags names** field search will be completed across the vault, use coma separator if you need more than 1 tag
Click Refresh
Update **Existing Characters** field with a pattern you are looking for in existing notes, set **Replacement Symbols**

---

Click Preview or `Enter` to see intermediate results(nothing will be changed/moved/renamed).

Click `Rename` whenever you done



## Update files based on tags



## API
- **folder location** - Files from which folder you need to rename
- **Symbols in existing files** - the symbols/characters that we have in the files
- **Replacement Symbols** - a new symbols that will be pasted instead
- **Files within the folder** - this is for information purpose

Rename Button
Rename files will start renaming all files by respective path.


## Motivation
This plugin was developed to cover my needs. Originally I've started to use my daily files with **_** delimiter.
So my files looked like this: 2022_01_01, over the time I realized other platform out of the box configured to prefer dashes, like this 2022-01-01

Here is many guides on how to rename files, what kind of script we need to run, what version of python or Node.js we need to install and so on.

Why Not to have this functionality build-in into Obsidian?

And rename a **bunch of files** and update their reference in code base respectively. So now you can rename a bunch of files from the directory and all imports also will be updated in a code-base


## Installing

The plugin in beta. To beta test, you can install the plugin using BRAT (see [BRAT > Adding a beta plugin](https://github.com/TfTHacker/obsidian42-brat#adding-a-beta-plugin) for further instructions).

## Support development

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/oleglustenko)
