# PACMAN
- sudo pacman-key --init
- sudo pacman-key --populate archlinux

# POWERTOP
- sudo powertop --auto-tune

# Installing

## VSCODE
- yay -S visual-studio-code-bin (official vscode from microsoft)
- sudo pacman -S code (open source version of vscode)

## Pamac
- pacman -S --needed git base-devel
- git clone https://aur.archlinux.org/libpamac-aur.git
- cd libpamac-aur
- makepkg -si
- cd ..
- git clone https://aur.archlinux.org/pamac-aur.git
- cd pamac-aur
- makepkg -si
