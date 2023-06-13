# i3wm-config
My i3 Windows Manager config files

This includes some custom key bindings, rofi power menu, rofi apps menu instead of dmenu.

## Setup
To setup, follow this steps:

1.  Install all needed packages
2.  Logout and select i3 WM in settings
3.  Create a config file (there will be a confirmation for that)
4.  Press: $mod+ENTER to open terminal (recommend setting MOD key to Windows ley)
5.  With cli replace current config file ~/.config/i3/config with custom config from here
6.  Move rofi-power-menu to ~/.config/i3/
7.  Replace /etc/i3status.conf with the custom i3status.conf (using sudo)
8.  Reload i3wm config and restart i3 using: $mod+Shift+c and $mod+Shift+r (note: this is the default key binding for reloading config and WM, the new one from custom config might be different)

## Packages to install

### Arch
On arch install this packages:
```
i3 i3status rofi i3lock xorg-xbacklight feh conky nitrogen redshift-gtk volumeicon xorg-setxkbmap maim xclip
```

### Fedora
On fedora install this packages:
```
i3 i3status rofi i3lock xbacklight feh conky nitrogen redshift-gtk volumeicon setxkbmap maim xclip
```

## Disable bip sound
Run this command to disable bip sound from i3:
```
sudo echo "blacklist pcspkr" >> /etc/modprobe.d/nobeep.conf
```

## Key bindings
To show later...
