# Alfred Zoxide

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/yihou/alfred-zoxide?sort=semver&style=flat-square)](https://github.com/yihou/alfred-zoxide/releases)
[![GitHub downloads](https://img.shields.io/github/downloads/yihou/alfred-zoxide/total?style=flat-square)](https://github.com/yihou/alfred-zoxide/releases/latest/download/NightShift.alfredworkflow)
[![GitHub issues](https://img.shields.io/github/issues/yihou/alfred-zoxide?style=flat-square)](https://github.com/yihou/alfred-zoxide/issues)
[![GitHub license](https://img.shields.io/github/license/yihou/alfred-zoxide?style=flat-square)](https://github.com/yihou/alfred-zoxide/blob/master/LICENSE)

A simple [Alfred][1] workflow to search and navigate directories that are saved in zoxide

Installation
1. Install library [Zoxide][2]
2. Install [alfred-zoxide][3] workflow.
3. All further updates are handled automatically.

## Usage
In Alfred, type `z` followed by search `query`. 

With the selected result, you can enter to open directory in terminal, 
or press `⌘` to open directory in Finder, 
or `⌃` to copy to clipboard.

<p align="center">
  <img width="1200" height="auto" src="images/demo.gif">
</p>


## Credits

The workflow makes use of the following:

[Zoxide][2] by Ajeet D'Souza as the backend to search for saved directories.

[OneUpdater][4] by Vítor Galvão for handling automatic updates.


[1]: https://www.alfredapp.com/
[2]: https://github.com/ajeetdsouza/zoxide
[3]: https://github.com/yihou/alfred-zoxide
[4]: https://github.com/vitorgalvao/alfred-workflows/tree/master/OneUpdater
