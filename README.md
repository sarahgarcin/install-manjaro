#Gigabyte P34G Manjaro postinstall
post installation configuration of Manjaro

## Update pacman and system
```sudo pacman -S pacman```
```sudo pacman -S manjaro-system```
```sudo pacman -Syu ```

##Configure Konsole
- Settings -> Manage Profil -> Edit

##Configure Kwallet
###Generate gpg encrypting key
https://wiki.archlinux.org/index.php/GnuPG
```gpg --full-gen-key```
RSA (sign only) and RSA (encrypt only)
4096 bits
1 year

##Install Basic Softwares
```sudo pacman -S vim kdeutils-kwalletmanager chromiun firefox firefox-firebug firefox-adblock-plus synapse zeitgeist filezilla bash-completion htop```
```yaourt -S retext python-markdown```

##Install needed Softwares
###Design softwares
```sudo pacman -S inkscape gimp scribus libreoffice```

### Developpement Software
```yaourt -S koala```
```yaourt -S sublime-text-dev```


### Desktop Software
```yaourt -S owncloud-client```
```yaourt -S dropbox```

## LAMP
