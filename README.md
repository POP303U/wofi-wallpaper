<div align="center"> 
<h2> wofi-wallpaper </h2>
Wallpaper changer script for wofi

</div>

## Foreword
It is recommended to use this script with my Hyprland config [hypr-dots](https://github.com/POP303U/hypr-dots).
If you want to use it with a different wallpaper path, wallpaper system or language that is all up to you.

## Installation

```
git clone https://github.com/POP303U/wofi-wallpaper.git ~/wofi/wofi-wall
chmod +x ~/wofi/wofi-wall/wofi-wallpaper
sudo cp ~/wofi/wofi-rice/wofi-rice-selector /bin
```

### Hyprland keybinding

```
bind $mainMod, B, exec, wofi-wallpaper
```

### Thanks for the inspiration!

- [rofi+pywal theme switcher](https://dev.to/mafflerbach/theme-switcher-based-on-rofi-and-pywal-4128)
