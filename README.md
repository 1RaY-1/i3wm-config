# My simple i3wm-config
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
8.  Set a wallpaper with nitrogen, you can use ```nitrogen --set-auto path/to/file```
9.  Reload i3wm config and restart i3 using: $mod+Shift+c and $mod+Shift+r

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

## Disable bip sound (Not obligatory)
Run this command to disable bip sound from i3:
```
sudo echo "blacklist pcspkr" >> /etc/modprobe.d/nobeep.conf
```

## Key bindings
To show later...

You can see the key bindings in the config file, note that if you don't know the key bindings, you will be unable to use the WM (any window manager will require you to know their key bindings).

## Screenshot
later...

### Caution
If you don't even know what window managers are and used to use a common desktop environment like Gnome or KDE, I recommend first watching a youtube video about them and then think if you really need it.

If you do something wrong with your OS, I AM NOT RESPONSIBLE for that.
