# ubuntu-18.04-basic-installation

## Setup configuration folders

```
mkdir -p /home/david/.config/bin
```

## Packages to install

```
apt install maven openjdk-11-jdk vim-gtk git ansible

apt install gmrun thunderbird firefox xterm thunar

apt install openbox obconf obmenu lightdm
```

### Setup openbox

```
mkdir -p ~/.config/openbox
cp config/openbox/rc.xml ~/.config/openbox
openbox --reconfigure
```

### Setup system configuration

```
cp .vimrc ~/
```
