# Nordix pacman wrapper for bulk remove package

 > Search and remove all package that matches, with pree view and confirm y/n before remove

```Fish
echo -e '\033[38;2;179;240;255m'

pacman-bulk-Rns
#======================================================#
 #       *  Nordix Tools - pacman bulk remove *       #
#======================================================#

Runs: pacman -Qq and pacman -Rns with confirmation y/n

Usage: pacman-bulk-Rns [pkg search]
Example: pacman-bulk-Rns libreoffice

#======================================================#
```

Example:
```Fish
pacman-bulk-Rns hypr
hyprcursor-frozen hyprgraphics-frozen hypridle-frozen hyprland-frozen hyprland-guiutils-frozen hyprland-protocols-frozen hyprland-qt-support-frozen hyprlang-frozen hyprlock-frozen hyprpicker-frozen hyprpolkitagent-frozen hyprtoolkit-frozen hyprutils-frozen hyprwayland-scanner-frozen hyprwire-frozen nx-hyprinstall xdg-desktop-portal-hyprland-frozen

Do you want to remove these packages? y/n
```
