# ubuntu-18.04-basic-installation

## Setup generic configuration

```
mkdir -p /home/david/.config/bin
cp .vimrc ~/
```

## Packages to install

```
apt install maven openjdk-11-jdk vim-gtk git ansible virtualbox

apt install gmrun thunderbird firefox xterm thunar

apt install openbox obconf obmenu lightdm
```

## Setup openbox

```
mkdir -p ~/.config/openbox
cp config/openbox/rc.xml ~/.config/openbox
openbox --reconfigure
```

## Programs to install not from packages

* IntelliJ
* Postman
** apt install libgconf-2-4
* Visual Studio Code
