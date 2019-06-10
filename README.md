# The Apps I Use and How To Tweak Things

This is intended as a personal reference because I'm new to Linux as a desktop OS and I've been distro hopping...and occasionally forgetting what apps I have enjoyed using.

## Command Line
* vtop (installed via "npm -g install vtop" after installing npm)
* tmux

## Gaming
* Steam
* Lutris (sudo add-apt-repository ppa:lutris-team/lutris)

## Gnome Shell Extensions
* Dynamic Panel Transparency

## Tweaks
### Transparent Launcher Bar
Either install dconf-editor and navigate to the same sections or enter into the commandline:
~~~~gsettings set org.gnome.shell.extensions.dash-to-dock transparency-mode 'FIXED'
gsettings set org.gnome.shell.extensions.dash-to-dock background-opacity 0.8
