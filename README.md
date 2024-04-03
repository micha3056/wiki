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
sudo adduser [NEWUSERNAME]

## start up with another user
wsl --user [NEWUSERNAME]

## remote connection:
localhost:3388

</details>