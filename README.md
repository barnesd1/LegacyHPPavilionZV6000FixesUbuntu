# Legacy Laptop - HP Pavilion ZV6000 Series - Fixes Ubuntu 20.04
## Update System
    sudo apt update -y && sudo apt upgrade -y && sudo apt autoremove -y
    sudo update-grub
    sudo reboot
## Install These
    sudo apt install barrier kodi -y
    sudo apt install zram-config -y
    sudo apt install gnome-tweaks -y
    sudo apt install stacer -y
    sudo apt install timeshift -y
    sudo apt install preload -y
    Download Chrome browser and save file
    sudo dpkg -i ~/Downloads/*.deb
## Move Applications Button
    gsettings set org.gnome.shell.extensions.dash-to-dock show-apps-at-top true
## Purge/Remove These
    sudo apt purge apport mesa-vdpau-drivers
    sudo apt purge firefox
    sudo apt purge cups
## Run Stacer
    Clean everything in System Cleaner
    Untick anything Power related in Services
## Run Settings
    Stop Search running
    In Privacy switch off everything
## Run Gnome Tweaks
    Make Workspaces to Static 1 Only

