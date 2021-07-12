# MobaxTerm：一款可替代SSH和Ftp的远程管理工具

市场上关于ssh远程终端管理工具非常之多，比如putty，xshell等，但是这些工具要么是收费，要么就是操作困难。今天要给大家介绍一款兼具SSH和FTP的管理工具：MobaxTerm。MobaxTerm是一款windows下的增强终端工具，它支持所有重要的远程网络工具SSH，X11，RDP，VNC，FTP，MOSH 等。最重要的是它是免费的，当然也有收费款，但是普通开发者几乎用不到其高级功能。

![MobaXterm main window](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogmobaxterm-main-window.png)

## MobaxTerm的主要特性

* 支持众多 Unix/Linux 命令 （bash、grep、awk、sed、rsync、...）
* 基于Putty重要特性而集成的SSH连接终端，同时支持SFTP文件管理功能
* 动态端口转发功能，支持多种协议：
* 支持同时多个窗口执行同一条命令



###SSH和SFTP文件管理

* 点击Session创建连接会话

![The Session button](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogsession-button.png)

* 输入ip、用户名

  ![image-20210714225730280](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210714225730280.png)

  

* 点击右侧sftp可管理文件

### 多终端分屏和多标签

* 点击split，可横向纵向 2 分屏和田字形 4 分屏，便于一个窗口管理多个远程连接

  ![image-20210714225712019](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210714225712019.png)



### 多窗口命令执行

* 点击MultiExec，可以用于同时向多窗口发送一条指令

  ![image-20210717114120774](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210717114120774.png)

  

### 端口动态转发

* 点击Tunneling，可用于端口转发，非常重要的一个功能

  ![The "Tunneling" button](https://mine-doc.oss-cn-beijing.aliyuncs.com/bloggraphical-ssh-tunnel-builder.png)
  
  ![image-20210717114133435](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210717114133435.png)
  
  

### 开启 linux 的远程桌面

* 点击创建session，输入远程ip和用户名，远程环境（Remote enviroment）选择Gnome desktop（前提是远程Linux安装Gnome）

  ![image-20210717114152367](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210717114152367.png)

### 支持VNC、RDP、Xdmp远程桌面

* 点击server，里面提供了众多远程桌面连接服务：TFTP、FTP、HTTP、SSH/SFTP、Telenet、NFS、VNC、Cron、Iperf

  ![img](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogaHR0cHM6Ly9hc2sucWNsb3VkaW1nLmNvbS9odHRwLXNhdmUvZGV2ZWxvcGVyLW5ld3MvdXNld2cyOHkzeC5qcGVnP2ltYWdlVmlldzIvMi93LzE2MjA.jpeg)

  

  

### 其他效率技巧

* 关闭自动断开SSH会话

  ![image-20210717113344453](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210717113344453.png)

  

* 使用 Windows 环境变量

  ![image-20210717114243624](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210717114243624.png)

  

  

* 右键快速复制粘贴

  ![image-20210717114215864](https://mine-doc.oss-cn-beijing.aliyuncs.com/blogimage-20210717114215864.png)

  



MobaxTerm产品主页：https://mobaxterm.mobatek.net/



