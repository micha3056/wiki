# wiki
its for documantation process

<details>
<summary>Ubuntu Xorg on Windows</summary>

## Sub intro

## install wsl
```
sudo apt update && sudo apt upgrade
sudo apt install xfce4 xrdp
sudo sed -i 's/3389/3388/g' /etc/xrdp/xrdp.ini

sudo /etc/init.d/xrdp start
```
## add another user
su root
apt-get install sudo -y
sudo adduser micha3057 sudo
chmod  0440  /etc/sudoers
RESTART WSL
sudo echo "Hello World!"

## start up with another user
wsl --user [NEWUSERNAME]

## remote connection:
localhost:3388

</details>