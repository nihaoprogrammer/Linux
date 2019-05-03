# 常用Linux命令  

* mv 移动(重命名)  
* cp 复制  -r 递归  
* rm 删除  -f 不提醒  
* gzip 压缩和解压缩  -d 解压  
* tar 打包与解包  
> -c 创建打包文件 
-x 释放打包文件  
-f 指定打包或解包文件的名称  
-z 打包时通过gzip格式压缩或解压  
-v 显示打包或解包的过程 
如:   
tar -zcvf /a.txt.tar.gz /a.txt
tar -zxvf /a.txt.tar.gz
