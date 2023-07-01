<div style="display: flex;">
<H1>Alfred Zoxide</H1>
<img src="images/icon.png" style="margin-left: 20px; margin-top: 40px; width: 40px; height: 40px;" alt="Logo"/>
</div>

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/yihou/alfred-zoxide?sort=semver&style=flat-square)](https://github.com/yihou/alfred-zoxide/releases)
[![GitHub downloads](https://img.shields.io/github/downloads/yihou/alfred-zoxide/total?style=flat-square)](https://github.com/yihou/alfred-zoxide/releases/latest/download/NightShift.alfredworkflow)
[![GitHub issues](https://img.shields.io/github/issues/yihou/alfred-zoxide?style=flat-square)](https://github.com/yihou/alfred-zoxide/issues)
[![GitHub license](https://img.shields.io/github/license/yihou/alfred-zoxide?style=flat-square)](https://github.com/yihou/alfred-zoxide/blob/master/LICENSE)

A simple [Alfred][1] workflow to search and navigate to directories that are saved in [Zoxide][2].

## Installation
1. Install library [Zoxide][2], see [Dependencies](#dependencies) for more details.
2. Install [alfred-zoxide][3] workflow.
3. All further updates are handled automatically.

## Usage
In Alfred, type `z` followed by search `query`. 

With the selected result, you can:
- press `⌅`(Enter) to open directory in terminal
- press `⌘`(Cmd) to open directory in Finder
- press `⌃`(Shift) to copy directory path to clipboard

<p>
  <img src="images/demo.gif" alt="demo.gif">
</p>

## Dependencies
[Zoxide][2] is required to be installed on your system.

Zoxide installation from [Zoxide][2] README:

> To install zoxide, use a package manager:
>
> | Repository      | Instructions                                                                                          |
> |-----------------|-------------------------------------------------------------------------------------------------------|
> | **[crates.io]** | `cargo install zoxide --locked`                                                                       |
> | **[Homebrew]**  | `brew install zoxide`                                                                                 |
> | [asdf]          | `asdf plugin add zoxide https://github.com/nyrst/asdf-zoxide.git` <br /> `asdf install zoxide latest` |
> | [conda-forge]   | `conda install -c conda-forge zoxide`                                                                 |
> | [MacPorts]      | `port install zoxide`                                                                                 |
>
> Or, run this command in your terminal:
>
> ```sh
> curl -sS https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/install.sh | bash
> ```


## Credits

The workflow makes use of the following:

[Zoxide][2] by Ajeet D'Souza as the backend to search for saved directories.

[OneUpdater][4] by Vítor Galvão for handling automatic updates.


[1]: https://www.alfredapp.com/
[2]: https://github.com/ajeetdsouza/zoxide
[3]: https://github.com/yihou/alfred-zoxide
[4]: https://github.com/vitorgalvao/alfred-workflows/tree/master/OneUpdater
