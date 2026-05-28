# 🌌 My Desktop Configuration

Welcome to my personal Linux desktop environment configuration. This repository stores all my dotfiles for a fast, beautiful, and highly productive workspace powered by the **Hyprland** Wayland compositor.

---

## 🛠️ Core Components

| Component | Software Used | Description |
| :--- | :--- | :--- |
| **Compositor** | [Hyprland](https://hyprland.org/) | Dynamic tiling Wayland compositor |
| **Status Bar** | [Waybar](https://github.com/Alexays/Waybar) | Highly customizable Wayland bar |
| **Terminal** | [Kitty](https://sw.kovidgoyal.net/kitty/) | GPU-accelerated terminal emulator |
| **Application Launcher** | [Wofi](https://hg.sr.ht/~scoopta/wofi) | Launcher and dmenu replacement for Wayland |
| **Shell** | Zsh / Bash | *[Change this to your preferred shell]* |

---

## 📸 Screenshots

> 💡 *Tip: Add some screenshots of your desktop here to show off your rice! Drag and drop images into GitHub, then paste the links below.*

| Clean | Dirty (Open Windows) |
| :---: | :---: |
| ![Clean Workspace](path/to/clean-screenshot.png) | ![Dirty Workspace](path/to/dirty-screenshot.png) |

---

## 🚀 Installation & Setup

> ⚠️ **Warning:** Do not run an install script blindly without reviewing it. Back up your existing configurations before applying these dotfiles.

### 1. Install Dependencies
Make sure you have the core packages installed. On **Arch Linux**, you can install them using:

```bash
sudo pacman -S hyprland hyprpaper hyprlock waybar dolphin mako kitty wofi satty
