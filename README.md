1) **Update**
```
sudo apt update && sudo apt upgrade -y
```
2) **Install Ubuntu Restricted Extras**
```
sudo apt install ubuntu-restricted-extras
```
3) **Flatpak and Flathub**
```
sudo apt install flatpak
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
4) **Gnome Software**
```
sudo apt install gnome-software gnome-software-plugin-flatpak
```
5) **AppImage Support**
```
sudo apt install libfuse2
```
6) **Gnome Extensions**
```
sudo apt install chrome-gnome-shell gnome-shell-extension-manager
```
