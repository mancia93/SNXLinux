# SNXLinux
install SNX vpn on Ubuntu &amp; Ubuntu based distros

```bash
sudo dpkg --add-architecture i386
sudo apt update
sudo apt-get install libc6:i386 libx11-6:i386 libpam0g:i386 libstdc++5:i386
```
# download file https://drive.google.com/file/d/1ddTlK1dpf9fD4d_MgceAbdMWx8E8UFHZ/view
```bash

cd /path to snx_install.sh
sudo chmod +x snx_install.sh
sudo ./snx_install.sh
 ```
# should appear 'Installation successfull'
#initiate with
```bash
snx -s 'server' -u 'user'
```
