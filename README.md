# Anya-Cursors
<p align="center">
	<img src="https://images.pling.com/img/00/00/79/33/24/2169016/anyacursors.jpg" width="350" height="300" alt="Anya-cursors logo">
</p>

## Features
- Complete cursor theme with multiple cursor states
- Multiple size options (16, 24, 32, 48 pixels)
- Hyprland configuration included
- XCursor compatible with all major desktop environments

## Installation

Clone the repository:
```
git clone https://github.com/Burhanverse/Anya-cursors
cd Anya-cursors
```

Run the installer:
```
./install.sh              # Local installation
sudo ./install.sh         # System-wide installation
```

## Configuration

**For Hyprland:**
Add this line to `~/.config/hypr/hyprland.lua`:
```
require("hyprland.cursor")
```

**For other desktop environments:**
See the [ArchWiki Cursor Themes guide](https://wiki.archlinux.org/title/Cursor_themes) for setup instructions.

## Uninstallation

```
# Local installation
rm -r $HOME/.icons/Anya-cursors*

# System-wide installation
sudo rm -r /usr/share/icons/Anya-cursors*
```

## Credits

- **NOR-DARKSTAR** - [Linux port](https://www.gnome-look.org/p/2169016)
- **Rachit-Pal** - [Windows cursor pack](https://github.com/Rachit-Pal/AnyaCursor)
