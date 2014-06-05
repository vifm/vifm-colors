Various colorschemes for [vifm](http://vifm.sourceforge.net/).
- Desert
- Matrix
- Solarized Dark
- Zenburn

The solarized-dark theme is based on [istib](https://github.com/istib)'s [version](https://github.com/istib/dotfiles/blob/master/vifm/vifm-colors).

# Get it #
If you would like to have just one theme you could download it via wget, for example:
`wget -P ~/.vifm/colors https://raw.githubusercontent.com/jubalh/vifm-colors/master/solarized-dark`

If you prefer to download all themes you could set it up with git, and stay up to date.

`rm -rf ~/.vifm/colors`

`git clone https://github.com/jubalh/vifm-colors ~/.vifm/colors`

To check for updates just type `git pull` in `~/.vifm/colors`.

# Set it #
Load with `:colorscheme theme-name` in vifm, or write `colorscheme theme-name` in vifm's configuration file `~/.vifm/vifmrc`.

If you have any color themes that are not in this repo, feel free to fork, add it and send me a pull request!
