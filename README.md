# JohnOS

![JohnOS Logo](https://joswinjohn.com/files/configs/Pictures/johnos-logo.png)

This is my pre-riced Arch Linux distro, equipped to write programs and notes in Neovim.

A few details about this setup:
| Config                 | Type                    |
| ---------------------- | ----------------------- |
| Window Manager         | i3-wm                   |
| Shell                  | fish                    |
| Text editor            | neovim                  |
| Compositor             | [picom (yshui)](https://github.com/yshui/picom)      |
| Status Bar             | polybar                 |
| Login Manager          | none                    |
| Launcher               | rofi                    |
| Notification Daemon    | dunst                   |
| Background             | feh                     |

## Installation
Follow the default [Arch installation guide](https://wiki.archlinux.org/title/Installation_guide)

once in [chroot](https://wiki.archlinux.org/title/Installation_guide#Chroot) run

```bash
sudo pacman -S - < /etc/pkglist
```

Alternatively you can use [archinstall](https://wiki.archlinux.org/title/Archinstall)
```bash
archinstall --config /etc/archinstall.json
```
