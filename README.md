Macish is based on the Ninix(which is based on Numix) and Xgtk theme.
It's a light theme with OSX like window controls.

[Ninix theme](https://github.com/ninixon/ninix)
[XGTK theme](https://github.com/joshiggins/xgtk-kxmylo)
[Numix Project](http://numixproject.org).

### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

or for local install only: $HOME/.themes/

To set the theme in Gnome, run the following commands in Terminal,

```
gsettings set org.gnome.desktop.interface gtk-theme "Macish"
gsettings set org.gnome.desktop.wm.preferences theme "Macish"
```

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "Macish"
xfconf-query -c xfwm4 -p /general/theme -s "Macish"
```

### Requirements

GTK+ 3.6 or above

Murrine theme engine

### Code and license

License: GPL-3.0+
