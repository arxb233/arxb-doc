---
title: 如何使用 Iperius Backup 进行自动备份
date: 2023-10-20 11:31:26
tags:
cover: https://www.iperiusbackup.com/img/logos/iperius_backup_logo_header.png
top_img: https://www.iperiusbackup.com/img/logos/iperius_backup_logo_header.png
---

# 如何使用 Iperius Backup 进行自动备份

::: tip 本文引用
本文出处，如有侵权请联系删除：
<a href="https://home.cnblogs.com/u/subsea/" target="_blank">https://home.cnblogs.com/u/subsea/</a>
<a href="https://www.cnblogs.com/subsea/" target="_blank">博客园主页：https://www.cnblogs.com/subsea/</a>
<a href="https://blog.csdn.net/SUBSEA123/" target="_blank">CSDN主页：https://blog.csdn.net/SUBSEA123/</a>
:::

##  环境准备
<p><strong><span style="color: rgba(255, 0, 0, 1)">备份工具--Iperius Backup Full--windwos平台软件</span></strong></p>
<p><strong><span style="color: rgba(255, 0, 0, 1)">备份支持文件、文件夹、图片文档音视频；最优秀一点支持常用数据库</span></strong></p>
<p>安装备份工具系统---windwos server 2012 R2</p>
<p>软件官网：<a href="https://www.iperiusbackup.com/" rel="noopener">https://www.iperiusbackup.com/</a></p>
<p>备份终端系统--win7/win server 2008R2</p>
<p>备份终端系统的SQL SERVER数据库及一部分文件夹</p>

## Iperius Backup Full功能介绍
<p><span style="font-size: 18px; color: rgba(255, 0, 0, 1)">为什么选择Iperius Backup Full？</span></p>
<p>1.不要钱，有破解：博主找了很长一段时间备份软件，大公司的备份软件基本都收费，小公司的多数比较难用，这个可以破解才是王道</p>
<p>2.功能多，涉及广：除了简单的支持备份文件、文件夹、音视频图片文档等</p>
<p>支持常用数据库，已测试备份过SQL SERVER及MYSQL，添加帐号就可以备份</p>
<p>支持FTP和SMB，有这两个灵活运用就更加方便了，添加帐号路径可以自动操作</p>
<p>带日志和计划，报错了可以看日志，有计划可以实现自动操作，香得一</p>
<p>&nbsp;</p>
<p><span style="font-size: 18px; color: rgba(255, 0, 0, 1)">备份作业：</span></p>
<p><span style="color: rgba(255, 0, 0, 1)">1.文件夹备份：</span>本地的文件夹，带SMB的路径文件夹，网络路径文件夹，NAS文件夹等等</p>
<p><span style="color: rgba(255, 0, 0, 1)">2.文件备份：</span>同上</p>
<p><span style="color: rgba(255, 0, 0, 1)">3.备份镜像：</span>还没试过，看介绍很牛B，可以把系统刻录成镜像用于恢复</p>

![](/IperiusBackup/1825093-20201101152839999-1665244098.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1)">4.FTP：</span>自带FTP客户端，可以直接跟配置FTP的机器做连接，然后实现FTP的自动下载与备份，可用于云服务器的备份</p>

![](/IperiusBackup/1825093-20201101152925430-650250774.png)

<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1)">5.ESXI/Vcenter：</span>支持连接VMware-VC跟ESXI帐号，虚拟机备份！</p>

![](/IperiusBackup/1825093-20201101153001693-1088201862.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1)">6.Hyper-v：</span>支持微软的虚拟机备份</p>

![](/IperiusBackup/1825093-20201101153029472-774029156.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1)">7.Exchange / Exchange Online (Office 365账号）：</span>备份EXchange邮箱</p>

![](/IperiusBackup/1825093-20201101153051416-97907404.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1)">8.SQL Server：</span>测试过，远程备份SQL server到本地，输入帐号即可</p>

![](/IperiusBackup/1825093-20201101153145739-1698219061.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1)">9.My SQL：</span>测试过，远程备份MYSQL到本地，输入帐号即可</p>

![](/IperiusBackup/1825093-20201101153244433-749811948.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1)">10.PostgreSQL：</span>没测试，原理同上</p>

![](/IperiusBackup/1825093-20201101153309102-1287355486.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1)">11.Oracle：</span>测试过，原理同上</p>

![](/IperiusBackup/1825093-20201101153559259-208383897.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="font-size: 18px; color: rgba(255, 0, 0, 1)">备份目的地：</span></p>
<p>1.本地文件夹</p>
<p>2.网络连接的路径：例如FTP,SMB,NAS或者灵活跟各设备存储运用，支持网络路径就行</p>
<p>3.云平台：主要是国外的-google，亚马逊，微软one drive</p>

![](/IperiusBackup/1825093-20201101152811664-1555989486.png)

<p>&nbsp;</p>
<p><span style="color: rgba(255, 0, 0, 1); font-size: 18px">备份类型与计划：</span></p>
<p>1.定时任务</p>
<p>2.自动任务</p>

![](https://blog.fanpin.icu/2023/10/20/IperiusBackup/1825093-20201101152430350-1442199672.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>3.备份类型：好完整备份，增量，差异基本都支持</p>

![](/IperiusBackup/1825093-20201101152404923-205421803.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="font-size: 18px; color: rgba(255, 0, 0, 1)">备份日志与提示：</span></p>
<p>1.支持邮箱提醒：技术好点的同学可以把这个用于邮件服务器，通过脚本和接口实现二次发送，推送到QQ，微信或者钉钉等应用，可以开发</p>

![](/IperiusBackup/1825093-20201101153938183-1188921449.png)

<p>&nbsp;</p>
<p>2.备份日志：报错了可以查询哪里出问题，优秀</p>

![](/IperiusBackup/1825093-20201101154142078-493096557.png)

<p>&nbsp;</p>

![](/IperiusBackup/1825093-20201101154307101-1966143759.png)

<p>&nbsp;</p>
<p><strong><span style="background-color: rgba(255, 255, 0, 1)">拓展与总结：</span></strong></p>
<p><strong><span style="background-color: rgba(255, 255, 0, 1)">1.区别去其他大公司的备份软件，部署CS或者BS架构，一台机器就可以了</span></strong></p>
<p><strong><span style="background-color: rgba(255, 255, 0, 1)">2.看官网介绍可以支持BS架构，但是要购买它家的Iperius console，购买后就可以实现web网站后台管理</span></strong></p>
<p><strong><span style="background-color: rgba(255, 255, 0, 1)">3.技术强点的同学可以再灵活运用一下，例如邮箱那一块用脚本推送到微信钉钉APP上，有报错第一时间处理；</span></strong></p>
<p><strong><span style="background-color: rgba(255, 255, 0, 1)">跟其他存储与网络设备结合，跨网络备份，例如云服务器的数据使用FTP自动备份到本地等等</span></strong></p>
<p><strong><span style="background-color: rgba(255, 255, 0, 1)">4.总的来说，只有有目标主机或者备份主机的相关帐号信息即可通过网络备份，比client的比起来简洁一点。</span></strong></p>
<p>&nbsp;</p>

##  操作流程
<p><span style="color: rgba(255, 0, 0, 1)"><strong><span style="font-size: 18px">举例：</span></strong></span><strong>自动备份一台局域网电脑的文件夹到本地</strong></p>
<p><strong>1.安装好Iperius Backup Full，保证与局域网电脑的网络正常通信（必要时关闭防火墙）</strong></p>
<p><strong>　<span style="color: rgba(255, 0, 0, 1)">　安装和破解略过了（百度很多），支持正版！！！！</span></strong></p>
<p><strong>2.将需要备份的文件夹开始SMB（文件共享），设置账户访问权限</strong></p>

![](/IperiusBackup/1825093-20201101160208700-302620325.png)

<p><strong>3.在Iperius Backup Full新建备份作业，选择文件夹。</strong></p>

![](/IperiusBackup/1825093-20201101160936975-1062776363.png)

<p><strong>4.根据向导提示，设置目标电脑SMB帐号，备份源，目的地，时间，周期计划等等</strong></p>
<p>&nbsp;添加SMB帐号：</p>

![](/IperiusBackup/1825093-20201101161053521-984263513.png)

<p>&nbsp;</p>
<p>&nbsp;设置源路径：</p>

![](/IperiusBackup/1825093-20201101161132319-964400009.png)

<p>&nbsp;</p>
<p>设置目的路径：</p>

![](/IperiusBackup/1825093-20201101161246125-1958758843.png)

<p>&nbsp;</p>
<p>设置备份计划：</p>

![](/IperiusBackup/1825093-20201101161320084-625501524.png)

<p>&nbsp;</p>
<p>高级设置：设置日志和文件压缩</p>

![](https://blog.fanpin.icu/2023/10/20/IperiusBackup/1825093-20201101161522021-313221326.png)

<p>是否使用电子邮件提醒：</p>

![](/IperiusBackup/1825093-20201101161433688-251134480.png)

<p>&nbsp;</p>
<p>摘要：</p>

![](/IperiusBackup/1825093-20201101161607279-40983475.png)

<p>&nbsp;</p>
<p>右键查看可操作性：</p>

![](/IperiusBackup/1825093-20201101161655449-671294453.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>自动备份一台云服务器的数据库到本地</strong></p>
<p><strong>1.云服务器安装配置FTP，将其中一个文件夹设置成可访问</strong></p>
<p><strong>　<span style="color: rgba(255, 0, 0, 1)">　推荐使用Fillzilla，做好权限设置与配置，再云防护墙开放端口</span></strong></p>
<p><strong>2.打开Iperius Backup FULL，使用自带的客户端添加帐号并测试到云服务器的FTP</strong></p>
<p><strong>FTP添加帐号：</strong></p>

![](/IperiusBackup/1825093-20201101164716393-1736128399.png)

<p>&nbsp;</p>
<p><strong>FTP测试：</strong></p>

![](/IperiusBackup/1825093-20201101164813040-1931709274.png)

<p>&nbsp;</p>
<p><strong>3.使用Iperius Backup Full远程备份数据库</strong></p>
<p><strong>添加SQL SERVER帐号：</strong></p>

![](/IperiusBackup/1825093-20201101165113102-274925785.png)

<p>&nbsp;</p>
<p><strong>选择要备份的数据库：</strong></p>

![](/IperiusBackup/1825093-20201101165223954-571079296.png)

<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong><span style="font-size: 15px">设置在云服务器数据库的备份路径（这里不能跨网络，所以先备份在云服务器上，在用FTP去自动下载这个文件夹到本地）</span></strong></p>

![](/IperiusBackup/1825093-20201101165609560-1509288079.png)

<p><strong><span style="font-size: 15px">4.设置备份计划时间等待，参照上方</span></strong></p>
<p><strong><span style="font-size: 15px">5.再添加一个FTP下载备份任务，将FTP文件自动下载到本机</span></strong></p>

![](/IperiusBackup/1825093-20201101165732793-349568606.png)

<p>&nbsp;</p>
<p><strong><span style="font-size: 15px"></span></strong></p>
<p><strong>6.设置备份计划时间等等&nbsp;</strong></p>

##  总结
<p>&nbsp;</p>
<p><span style="font-size: 18px; color: rgba(255, 0, 0, 1)">软件功能十分强大的，但是网上的参考资料不多，真正愿意尝试备份的朋友可以静下来来好好研究测试一下</span></p>
<p><span style="font-size: 18px; color: rgba(255, 0, 0, 1)">博主测试后已在生成环境部署，通过SMB,FTP与其他存储设备，已经形成自动备份数据库、文件夹资料等</span></p>
<p><span style="font-size: 18px; color: rgba(255, 0, 0, 1)">若有疑问可以在官网里面搜一搜，用谷歌浏览器可以翻译网页&nbsp;</span></p>
<p><span style="font-size: 18px; color: rgba(255, 0, 0, 1)">可能现在还没有人来重视这一块，但博主相信此文以后绝对会给大家带来一些帮助！</span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>　　<br></strong></p>
<p>&nbsp;</p>