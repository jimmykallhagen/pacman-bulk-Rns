# Nordix pacman wrapper for bulk remove package

**Part of:** [Nordix](https://github.com/jimmykallhagen/Nordix)  
**Author:** Jimmy Källhagen  
**License:** GPL-3.0-or-later

---

 > Search and remove all package that matches, with pree view and confirm y/n before remove

---

```Fish
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

Example:
```Fish
pacman-bulk-Rns nordix-cli
 nordix-cli-arch nordix-cli-zfs

Do you want to remove these packages? y/n
y
[sudo] password for core:
checking dependencies...

Package (2)      Old Version  Net Change

nordix-cli-arch  1.0-1         -0.18 MiB
nordix-cli-zfs   1.0-1         -0.09 MiB

Total Removed Size:  0.26 MiB

:: Do you want to remove these packages? [Y/n]
```
