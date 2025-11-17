<img width="300" height="300" alt="aether-linux-logo(1)" src="https://github.com/user-attachments/assets/7433519d-60e4-449b-b229-9fe0e6df5113" />


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

---

# System Requirements

All configurations require:
- 64-bit x86_64 processor
- Network access for installation (live ISO is usable offline)
- Minimum 4 GB installation target size
- For NVIDIA GPUs nvidia-dkms is recommended.

## Minimal
- CPU: Dual-core (any 64-bit Intel/AMD)
- RAM: 1 GB (DDR3/DDR4)
- Storage: 4 GB
- GPU: Any GPU supporting OpenGL 4.1+
This configuration suprisingly runs. Useful if you want to test this distro in a VM on a device that would go into the **Minimal Recommended** category.

## Minimal Recommended
- CPU: 4 Cores
- RAM: 4 GB (DDR4)
- Storage: 64 GB (SSD/HDD)
- GPU: Any Mesa-supported GPU (Intel/AMD/NVIDIA).
General use, light multitasking, no slowdown in base system.

## Recommended
- 4-8 Cores
- RAM: (DDR4)
- Storage: 128 GB (SSD/HDD)
- GPU:
  - Any GPU with proper **Mesa** support
  - Intel UHD (2015+)
  - AMD GCN 2.0 (R9/R7 200) or newer
  - NVIDIA with nvidia-dmks, installable via scripts.
This configuration makes personal use ideal.

## High-performance
- 8+ cores @
- 32 GB+ GB of RAM (DDR4/DDR5)
- Modern Intel/AMD/NVIDIA GPU

# Screenshots/recordings

## <img width="1616" height="1010" alt="scr" src="https://github.com/user-attachments/assets/8c5c0fdc-e0ff-4b08-bb24-f3c1e1345d48" />
screenshots

## videos

https://files.catbox.moe/5cu44c.mp4

# Downloads
[Latest ISO (aetherlinux-2025.11.17-x86_64)](https://mega.nz/file/WlwBED7B#L5c55MZvcBiGWWqUyJVzh7fgTLs3aiKtrWOdjxsPrUA)
