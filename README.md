# i3wm Config

A lightweight, Gruvbox-inspired i3wm configuration built for speed, simplicity, and aesthetics.

![Wallpaper](finalimg.jpg)

## Included Configurations

| File | Description |
|------|-------------|
| `config` | Main i3 configuration |
| `picom.conf` | Picom compositor configuration |
| `config.ini` | Polybar configuration |
| `launch.sh` | Polybar launch script |
| `config.conf` | Rofi configuration |
| `black-outline.rasi` | Rofi theme |
| `alacritty.toml` | Alacritty terminal configuration |
| `conky.conf` | Conky system monitor |
| `dunstrc` | Dunst notification daemon |
| `tree_tiler.py` | Tree-based tiling helper script |
| `wallpaper.jpg` | Desktop wallpaper |
| `mylogo.txt` | Custom logo used in the setup |

## Features

- 🌲 i3 Window Manager
- 🎨 Gruvbox-inspired theme
- 🖥️ Alacritty terminal
- 🌫️ Picom transparency & effects
- 📊 Polybar
- 📈 Conky system monitor
- 🔔 Dunst notifications
- 🔍 Rofi application launcher
- ⚡ Lightweight and highly customizable

## Installation

Clone the repository:

```bash
git clone https://github.com/rin1wav/i3wm-config.git
```

Copy the configuration files:

```bash
cp config ~/.config/i3/config

cp alacritty.toml ~/.config/alacritty/

cp picom.conf ~/.config/picom/

cp config.ini ~/.config/polybar/
cp launch.sh ~/.config/polybar/

cp config.conf ~/.config/rofi/
cp black-outline.rasi ~/.config/rofi/

cp conky.conf ~/.config/conky/

cp dunstrc ~/.config/dunst/
```

Make the Polybar launcher executable:

```bash
chmod +x launch.sh
```

## Dependencies

- i3wm
- Picom
- Polybar
- Conky
- Alacritty
- Rofi
- Dunst
- Feh
- Nerd Fonts / JetBrains Mono (recommended)

## Preview

Add screenshots here once your setup is finished.

```
assets/
├── desktop.png
├── terminal.png
└── rofi.png
```

## Notes

This configuration is continuously updated as I customize my Linux desktop. Feel free to fork the repository and use any part of it in your own setup.

If you encounter any issues or have suggestions, feel free to open an issue.

---

Made with ❤️ using i3wm.
