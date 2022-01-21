# Gnome-breeze
simple script to build Gnome theme from kde colorscheme `~/.local/share/color-schemes/<colorscheme>.colors`

The original work is at here [Breeze for Gtk](https://invent.kde.org/plasma/breeze-gtk)

I have just modified the `./src/build_theme.sh` script to work properly

## Needed tools

```bash
python3
sassc
```

`sudo sh build_theme.sh -c <colorscheme> -t /usr/share/themes/<ThemeName you wanna give.>`
