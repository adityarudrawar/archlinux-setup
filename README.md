# archlinux-setup

## Volume Control
```
sudo pacman -S pipewire pipewire-pulse wireplumber
```
Then restart
```
systemctl --user restart pipewire wireplumber
```
Install Volumne control via GUI
```
sudo pacman -S pavucontrol
```

## Waybar installation

```
sudo pacman -S ttf-jetbrains-mono
```

## Bluetooth installation and configuring

1. Required Packages

```
sudo pacman -S bluez
sudo pacman -S bluez-utils
```

2. Make sure btusb module is loaded. If it is not, load the module
3. Start/enable bluetooth.service

4. GUI for bluetooth
 ```
sudo pacman -S blueman
 ```
5. Open Bluetooth Manager via App-tray now
