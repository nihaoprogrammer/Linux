# Linux
Linux折腾记

# Manjaro
*U盘启动
>F7-->Security-->Secure Boot Control(Disabled)-->Boot-->CSM Support(Enabled)-->F10
>安装后重启的时候把U拔掉。

*Google浏览器安装SwitchyOmega不能添加：  
>在命令行执行  
$google-chrome & --enable-easy-off-store-extension-install  

FAQ(常见问题汇总):
* different between 'zsh' and bash
> zsh >= bash
* How to fix “unable to lock database” error in Arch linux
>$ rm /var/lib/pacman/db.lck
* Manjaro Deepin连不上无线网
>sudo nano /etc/NetworkManager/NetworkManager.conf  

>systemctl restart NetworkManager  
* 挂载硬盘
[Manjaro(linux)下挂载硬盘](https://www.jianshu.com/p/0098ee403e77)  
*基本配置
>[Manjaro安装与基本配置](https://my.oschina.net/langxSpirit/blog/1647000)   
>[Manjaro 上手使用简明教程](https://wenqixiang.com/manjaro-guide/)
* 美化  
>[Manjaro Linux下炫酷zsh的安装配置（powerline必不可少）](https://www.lulinux.com/archives/1306)  
>[powerline-shell](https://github.com/b-ryan/powerline-shell)  
>[简单的manjaro安装powerline及vim zsh配置](https://blog.csdn.net/z924139546/article/details/79815788)  

