# Arch Linux Installer (Arch repo and Aur)

## Only for Arch linux understanding users -> [Arch Linux Installation Guide](https://wiki.archlinux.org/index.php/Installation_guide)
### auto install for VirtualBox (/dev/sda) and laptops with settings by Koljasha :-)

***
#### Ru localization is default; for change:
* `./installer` lines : 11 - 12
* `./chroot`    lines : 3 - 14

#### Start from [archlinux.iso](https://archlinux.org/download/) then:
* `pacman -Sy git`
* `git clone https://github.com/koljasha/archlinux_installer`
* `cd archlinux_installer && ./installer`

***
#### [Arch Linux Installation Guide](https://wiki.archlinux.org/index.php/Installation_guide)

* `./installer` - install system like [Arch Linux Installation Guide](https://wiki.archlinux.org/index.php/Installation_guide)
* `./chroot` *(run from ./installer)* - install system in arch-root mode like [Arch Linux Installation Guide](https://wiki.archlinux.org/index.php/Installation_guide#Chroot)
* `./packages` - install desktop environments (Openbox, i3wm), packages and settings it

***
#### After install run:
* `lxappearance` - reselect theme (for qt apps theme)
* `condaupdate` - update python conda environments
