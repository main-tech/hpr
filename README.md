# HyprLand Configuration

This is main-tech's configuration for HyprLand,  It has been tested on Arch Linux.

## Prerequisites

Before using this HyprLand configuration, make sure you have the following packages installed:

- hyprpaper: Sets wallpaper for the desktop.
- waybar: Provides a status bar for the desktop.
- dunst: A notification daemon.
- xdg-desktop-portal-hyprland: Enables swift communication between applications and the compositor through D-Bus.
- polkit-kde-agent: Displays a password prompt whenever an application needs elevated privileges.
- pipewire: Required for screen sharing.
- wireplumber: Required for screen sharing functionality.
- qt5-wayland: libray
- qt6-wayland: libray
- cliphist    a clipboard manager
- grim and slurp     for screenshot 
- brightnessctl A program to read and control device brightness
- wlsunset for filtering blue light
- udiskie and udisks2 for automatically mounting
- nautilus,  gnone file manager
- alacritty, terminal emulator
- set Alacritty as the default terminal emulator instead of xterm, execute the command: "sudo ln -T /usr/bin/alacritty /usr/bin/xterm". Remember that some programs might rely on xterm as the default, so ensure they are compatible with Alacritty before proceeding. If xterm is installed, uninstall it to avoid conflicts
