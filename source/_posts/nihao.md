---
title: realm & gost 一键转发脚本
top_img: https://ps.ssl.qhimg.com/t0260e9a57cbf5084f4.jpg
cover:: https://ps.ssl.qhimg.com/t0260e9a57cbf5084f4.jpg
copyright_author: false
main_color: #708fff
thumbnail: https://hexo.io/themes/screenshots/Again.jpg
abbrlink: 10739
---
realm脚本：

更新到最新的realm版本v2.6.2

新增了定时重启

新增了本地端口自定义

新增了转发备注
![Example Image](https://hexo.io/themes/screenshots/Again.jpg)
2024.10.8 12:38 更新 开启了UDP转发

2024.10.9 12:44 修复了定时重启失效的问题

2024.10.11 16:07 修复了重启无法自动启动的问题（多生成一行[Network],启动不了删除一个Network）

2024.10.22 12:40 监听地址仅ipv4修改成所有ipv4和ipv6
```
wget -N https://raw.githubusercontent.com/qqrrooty/EZrealm/main/realm.sh && chmod +x realm.sh && ./realm.sh
```
再次启动脚本


```
./realm.sh
```

如若更新脚本，请先删除脚本(不需要卸载)，再运行安装脚本
```
rm realm.sh
```
仓库：EZrealm
NS原贴：https://www.nodeseek.com/post-77509-1

gost脚本：

更新到最新的gost版本v2.11.5
2024.10.9 12.44 修复了定时重启失效的问题
```
wget --no-check-certificate -O gost.sh https://raw.githubusercontent.com/qqrrooty/EZgost/main/gost.sh && chmod +x gost.sh && ./gost.sh
```
再次启动脚本
```
./gost.sh
```
仓库：EZgost
原项目地址：https://github.com/KANIKIG/Multi-EasyGost

大佬勿喷，纯代码小白。。靠着gpt慢慢改出来的 
可能会有BUG(?)，我自己测试应该没啥问题。如果有BUG可以帖子留言，能修的话我尽量修一下
仅在debian上测试。其他系统请自行测试
全开源代码，放心食用