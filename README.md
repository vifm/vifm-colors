# vifm-colors

Various colorschemes for [vifm](https://vifm.info/):
- astrell (by astrell)
- darkdesert (by langner)
- Default
- desert
- dracula (by EgZvor)
- g80
- gruvbox (by laur89)
- iceberg (by puven12)
- lucius (by francogonzaga)
- matrix
- mc-like (by Petteri Knihti)
- molokai (by Miguel Madrid Mencía)
- near-default
- onedark (by mroavi)
- palenight (by mroavi)
- ph (by pihao)
- reicheltd-light (by reicheltd)
- semidarkdesert (by clausED)
- snowwhite (by durcheinandr)
- solarized-dark
- zenburn
- zenburn_1 (by frgm)

The solarized-dark theme is based on [istib](https://github.com/istib)'s [version](https://github.com/istib/dotfiles/blob/master/vifm/vifm-colors).

## Installation

### Distribution
Some distributions offer a package for vifm color schemes. In this case you can install them easily using your package manager.

#### openSUSE

```
zypper in vifm-colors
```

### Manual
If you would like to have just one theme you could download it via wget, for example:

`wget -P ~/.vifm/colors https://raw.githubusercontent.com/vifm/vifm-colors/master/solarized-dark.vifm`

If you prefer to download all themes you could set it up with git, and stay up to date.

`rm -rf ~/.config/vifm/colors`

`git clone https://github.com/vifm/vifm-colors ~/.config/vifm/colors`

To check for updates just type `git pull` in `~/.config/vifm/colors`.

*Note:* replace `~/.config/vifm` with `~/.vifm` in commands above if you store your configuration there.

## Preview
A preview of all color themes contained in this repository are available at [the official vifm site](https://vifm.info/colorschemes.shtml).

## Set a theme
Load with `:colorscheme theme-name` in vifm, or write `colorscheme theme-name` in vifm's configuration file `~/.config/vifm/vifmrc`.

If you have any color themes that are not in this repo, feel free to fork, add it and send a pull request!
