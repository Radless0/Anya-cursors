# Anya-Cursors
<p align="center">
	<img src="https://images.pling.com/img/00/00/79/33/24/2169016/anyacursors.jpg" width="350" height="300" alt="Anya-cursors logo">
</p>

Anya Cursor theme

## Features
- Complete cursor theme with multiple cursor states
- Hyprland configuration file included (`cursor.conf`)
- Persistent cursor settings that survive reboots
- Multiple size options (16, 24, 32, 48 pixels)
- Compatible with both XCursor and modern desktop environments

## Installation

### Installer
To use the installer, clone the repository and go inside it.
```
git clone https://github.com/Burhanverse/Anya-cursors
cd Anya-cursors
```
Then, run the installer script. For local installation, use
``` 
./install.sh
```
And for system wide installation use:
``` 
sudo ./install.sh
```

### Set the cursor theme

#### For Hyprland Users
This repository includes a `cursor.conf` file specifically for Hyprland users. To use it:

1. **Import the configuration** by adding this line to your `~/.config/hypr/hyprland.conf`:
   ```
   source = /path/to/Anya-cursors/cursor.conf
   ```
   Or copy the contents directly into your main config file.

2. **Restart Session** or reboot system.

The configuration includes:
- Environment variables for XCursor theme and size
- Persistent cursor settings that survive reboots
- GTK application compatibility
- Multiple cursor size options (16, 24, 32, 48)

**Note**: This configuration uses XCursor format (not Hyprcursor) as it provides better compatibility and the cursor theme persists properly across sessions.

#### For Other Desktop Environments
There are various ways to set this (or another) cursor theme.</br>
You will find all the needed information on this [ArchWiki](https://wiki.archlinux.org/title/Cursor_themes)

### Uninstallation

If you installed it locally, run this command in your terminal: 
```
rm -r $HOME/.icons/Anya-cursors*
```
And if you installed it system-wide use:
```
sudo rm -r /usr/share/icons/Anya-cursors*
```

## Credits

[NOR-DARKSTAR](https://www.gnome-look.org/p/2169016) For linux port.  
[Rachit-Pal](https://github.com/Rachit-Pal/AnyaCursor) Windows cursor pack (source)





