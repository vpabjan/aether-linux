# Aether Linux

Aether Linux is an Arch-based distribution focused on user-friendliness, aesthetics, and a clean Hyprland experience.  
It is rolling-release and pulls directly from the official Arch Linux repositories, ensuring a fully up-to-date and bleeding-edge system.

## System Overview

- **Base:** Arch Linux
- **Init system:** systemd
- **Bootloader:** GRUB
- **Display protocol:** Wayland
- **Desktop environment / WM:** Hyprland
- **Networking:** iwd (with systemd-networkd)
- **Audio:** PipeWire
- **Login manager:** ly
- **Shell:** bash

## Preinstalled Software

- **Terminal:** Alacritty  
- **Application launcher:** Rofi (drun mode)
- **Task manager:** btop (inside alacritty)
- **Web browser:** Firefox  
- **File manager:** Nemo
- **Media player:** mpv
- **Text editor:** Kate (subject to change)  
- **Image viewer:** imv  
- **Packages & AUR:** base-devel + yay  
- **Hyprland utilities:** hyprpaper, hyprlock, hypridle  
- **Screenshot utility:** hyprshot
- **Flexing utility** fastfetch

## Work-in-progress features
- A script library for simplyfing the Arch workflow
- A driver manager (mainly graphics)
- A hyprland configuration manager
- Yay as part of the system (currently an install script is present)
- Custom themes
- Aether Linux centre, a GUI program for managing settings and quick access (currently a python script)

## Complete features
- Full configs for:
  - Hyprland
  - Hyprpaper (A hint and non-hint wallpaper included)
  - Alacritty
  - Waybar
- Customized GRUB

<img width="1920" height="1080" alt="2025-11-17-031518_hyprshot" src="https://github.com/user-attachments/assets/dcbc9d89-c1fe-4b26-8f2d-ddd00d9beda8" />Aether running under kvm/qemu

https://github.com/user-attachments/assets/ef3a8bfa-7e61-4d81-afbc-b394cfce0c19
