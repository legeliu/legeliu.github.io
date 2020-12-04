## Welcome to legeliu web site

记录自己学习及实践笔记。

建立主页，用github.io命名，不要用github.com，已证实不好用，主页网址是 [legeliu](https://legeliu.github.io/)，欢迎访问。


## 家庭多媒体系统建立

## 硬件环境

移动宽带自带光猫、交换机、总机（All in one）、 AJ7400、台式机、笔记本、平板、手机、盒子等若干。

## 软件环境

总机为中心，搭建各环境All in one，总机为Dell Wyse瘦客户机，AMD G-T56N，4G内存，1T笔记本机械硬盘，性能很弱，价格谜之高企。

### 操作系统-unRaid

试过群晖（图形界面友好，支持Docker，虚拟机不成功，操作不流畅）、OMV（图形界面友好，支持Docker，操作流畅，文件夹各种权限不方便），最终选择unRaid，Docker、虚拟机简单易用，各种流畅，已稳定运行很久。

#### Docker

  -transmission

    PT挂种神器，自带UI太弱，更换WebUI后不太稳定，种子各种警告及错误，自行恢复。

  -deluge

    PT下载主力工具。

  -qbittorrent

    PT备用工具。

  -aria2

    各种其它链接、协议类下载工具。

  -tinymediamanager

    因为被墙，搁置不用，另一途径解决。

#### Virtual Machine（VM）

  -lean openWRT

    虚拟机运行，酸酸乳Plus+，作为旁路由。

  -alpine Linux

    下载虚拟机镜像，文件只有38M，分配5G空间足矣。安装了Docker环境，开机挂载unRaid的共享文件夹，用tmm刷海报、同人画等各种影视资料。
  
    -Docker-tinymediamanager

    因为被墙，在虚拟中以Docker运行，通过旁路由可以正常刮削电影资料及图片。
  
    -Docker-tinyRSS

    在虚拟中以Docker运行，且通过旁路由，可订阅一些外文资料，手机Reeder可用Fever插件为客户端，本地浏览，速度很快。
  
### 电视盒子-N1

    仅作为电视盒子应用，刷Rush固件，运行流畅无广告。安装Kodi作为播放器，挂载unRaid共享盘，千兆内网4k原盘无卡顿，IPTV看电视。

### 音乐播放-AJ7400

    作为收音机、播放器、闹钟，闲置手机插在Dock上挂载unRaid共享文件夹，可播放歌曲，也可播放在线流媒体。
  
### 台式机-win10

    作为重要文件存储及备份中心，按需开机。

### 笔记本-windows&mac

    挂载unRaid共享文件夹，临时及常用文档存储存在共享文件夹中，不占用本机空间，局域网内无线传输速度尚可接受，大文件可通过插网线传输。

  
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
