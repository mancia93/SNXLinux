# SNXLinux
install SNX vpn on Ubuntu &amp; Ubuntu based distros

```bash
sudo dpkg --add-architecture i386
sudo apt update
sudo apt-get install libc6:i386 libx11-6:i386 libpam0g:i386 libstdc++5:i386
```
### download file https://supportcenter.checkpoint.com/supportcenter/portal/user/anon/page/default.psml/media-type/html?action=portlets.DCFileAction&eventSubmit_doGetdcdetails&fileid=22824
```bash

cd /path/to snx_install_linux30.sh
sudo chmod +x snx_install_linux30.sh
sudo ./snx_install_linux30.sh
 ```
### should appear 'Installation successfull'
### initiate with
```bash
snx -s 'server' -u 'user'
```
### to disconnect
```bash
snx -d
```
