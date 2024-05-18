# 233v2installsh4mainland

自用小改 233boy v2ray sh 脚本  
获取ip网址从1111改到携程  
下包地址改到ghproxy  

### 注意安装完毕后使用脚本修改设置依然会报获取不到ip
### 需要把下面写的第二个文件改了  

- - -
脚本raw地址  
`https://raw.githubusercontent.com/bilibili33/233v2installsh4mainland/main/ins.sh`  

食用方法（建议先手动把unzip装了）  
`bash <(wget -qO- -o- https://raw.githubusercontent.com/bilibili33/233v2installsh4mainland/main/ins.sh)`  
或者  
用wget下载，chmod加权，执行  

- - -
安装完毕后你可能需要修改的文件（如果你啥也不改那放着就行）  
1. `/etc/v2ray/sh/src/download.sh`  这是更新啊啥的
2. `/etc/v2ray/sh/src/core.sh`  脚本核心，找到get_ip方法后把export行内引号内容改成和我这个脚本里的get_ip方法一样就行了

- - -
[源wiki](https://233boy.com/v2ray/v2ray-script/)  
[源repo](https://github.com/233boy/v2ray/tree/master)  
