# Debian 8.x (Jessie) Cinnamon Cheat Sheet

This cheat sheet provides tips and tricks for [Debian 8.x (Jessie)](https://www.debian.org/releases/jessie/) and the [Cinnamon Desktop](https://github.com/linuxmint/Cinnamon).

## Debian 8.x
* Installing `.deb`packages: `sudo dpkg -i <package>.deb`


## Cinnamon

* Changing the style of the Panel (Taskbar):    
  Edit `/usr/share/cinnamon/theme/cinnamon.css` (`sudo`) and change the style of the `#panel` selector.

* Make Nautilus the default file manager:    
  `xdg-mime default nautilus.desktop inode/directory application/x-gnome-saved-search`

* Pin program icon to Panel / Taskbar (beneath the WebStorm / Chrome etc. icon in the screenshot):   
![](images/pinprogramtopanel.png)
