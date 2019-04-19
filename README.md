# Linux
Linux的学习笔记
# Ubuntu
ubuntu18.04 Google浏览器安装SwitchyOmega不能添加：
>在命令行执行  
$google-chrome & --enable-easy-off-store-extension-install

# Manjaro

FAQ:
* different between 'zsh' and bash
> zsh >= bash
* How to fix “unable to lock database” error in Arch linux
>$ rm /var/lib/pacman/db.lck
* Manjaro Deepin连不上无线网
>sudo nano /etc/NetworkManager/NetworkManager.conf  
复制下面内容，回车
>[device]  
wifi.scan-rand-mac-address=no  

>systemctl restart NetworkManager
*基本配置
>[Manjaro安装与基本配置](https://my.oschina.net/langxSpirit/blog/1647000)   
>[Manjaro 上手使用简明教程](https://wenqixiang.com/manjaro-guide/)
