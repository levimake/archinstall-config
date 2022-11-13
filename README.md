# archinstall-config
The repository contains my archinstall configuration files which lets you install the required packages and sets the system up all in a single command. 
Since, we have a guided installer for arch linux, these configs makes it more easier.

## How to use the script 
```
git clone https://github.com/levimake/archinstall-config
cd archinstall-config
chmod +x ./install.sh
./install.sh
```

## Who this script is for ?
This script specifically installs a minimal KDE environment (not the complete KDE-Applications and DE)
and other required packages for my laptop LENOVO IDEAPAD GAMING 3 15ACH6.

The specific packages for my laptop are:
- The AMDGPU and Nvidia related components
- ACPI_CALL

Other packages include:
- Minimal set of KDE applications
- maim for screenshot utility
- mpv as the media player
- zathura as the pdf viewer
- firefox as the web-browser
- vim, htop
- GIMP, Kdenlive for the creative suite
- Libreoffice for office applications

Users could create your own configs from the sample.

## TODO
- [ ] Include post-install commands to set the following:
  - [ ] Install yay - package manager for AUR
  - [ ] Install deadbeef (audio player) and optimus-manager (GPU-switcher)
  - [ ] Enable sddm and NetworkManager
- [ ] Optimus-Manager tweaks:
  - [ ] Use hybrid on default startups
  - [ ] Use integrated GPU on battery startup and nvidia on ext. power startup
- [ ] Enable Conservation Mode with a prompt (this extends the battery life by limiting the charging to 60% if you prefers using the laptop on external power for long) (this should be asked as a question so users could opt out)
- [ ] Include other tweaks to include more lenovo laptop specific features (rapid charging, perfomance modes)
- [ ] Make the installer silent 👍
