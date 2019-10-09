下载完什么都不用写，直接起服务，感受一下

##### 起服务
1. 双击 nginx.exe
2. 或者 start nginx 启动Nginx

如果服务没有起来，说明，你文件夹目录有中文，或者你加的代码有错误

##### 关闭服务
nginx -s stop 快速停止和关闭Nginx

> 要经常重启关闭，否则改的东西不生效

##### 一些命令

nginx的启动和关闭
nginx -h 查看帮助信息
nginx -v 查看Nginx的版本号
nginx -V 显示Nginx的版本号和编译信息
start nginx 启动Nginx
nginx -s stop 快速停止和关闭Nginx
nginx -s quit 正常停止或关闭Nginx
nginx -s reload 配置文件修改重新加载
nginx -t 测试Nginx配置文件的正确性及配置文件的详细信息


#### 主要看的 地方

主要配置：
conf/nginx.conf
文件放的地方：
html/

可以参考的文章：
https://blog.csdn.net/qq_36125138/article/details/84144932


#### nginx报错的一些情况

1. 端口被占
2. 文件夹有中文名字
3. 注释 用的不是 #，导致错误