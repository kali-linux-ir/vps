
## Installation 
## 1.
<img src="https://img.shields.io/badge/Update%20_&_%20Upgrade-green">

  ```html
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```
  
## 2.0
<img src="https://img.shields.io/badge/Login_Root%20VPS-green">

* Login ke VPS dan Aktifkan Root Sementara

  
```html
sudo su
cd
cd
```

## 2.

  <img src="https://img.shields.io/badge/Buat_Akses_Root%20VPS-green">

* Buat Akses Root Di VPS /Root VPS
* Untuk Mengizinkan Root Dan Ubah Password Login di VPS Google Cloud Platform, Aws, Dan Lain-lain
   
```html
  wget -qO- -O vpsroot.sh https://raw.githubusercontent.com/kali-linux-ir/vps/main/vpsroot.sh && bash vpsroot.sh
  
```
  
### 3.

  <img src="https://img.shields.io/badge/Install_Semua_Layanan_VPN%20-green">

* Install Semua Layanan VPN /Install All VPN Service
   
```html
rm -f setup.sh && apt update && apt upgrade -y && update-grub && sleep 2 && apt-get update -y && apt-get upgrade && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/kali-linux-ir/vps/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
  
```
  
