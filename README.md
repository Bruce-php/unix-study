# lunix发展史概述
<h4>服务器</h4>
1U=1.75inches=44.45millinmeters  
Web服务器多采用1U服务器;  
应用服务器和数据库级别多采用U2服务器,拓展性更强,能连接更多的存储器增加数据处理能力。
<h4>Unix诞生</h4>
1969年美国贝尔实验室的KenThomson(肯*汤普森)、Dennis Ritchie(丹尼斯*里奇)发明;  
1972年C语言诞生;  
1973年Unix用C语言改写完成(最知名的是加州大学的伯克莱分校的BSD unix系统);  
1991年,Linux系统正式发布;
<h4>GNU组织</h4>
GNU(GUN`s Not unix)是由Richard Stallman公开发起,目标是创建一套完全自由的操作系统。  
官方网站www.gnu.org
<h4>Linux内核</h4>
Linus Benedict Torvalds Linux系统内核创建者;  
官方网站(www.kernel.org)

#RHEL 学习规划
<h4>Linux各发行版本统计数据与排名</h4>
统计网站www.distrowatch.com
<h4>Redhat认证等级</h4>
RHCSA(Red Hat Certified System Administrator):红帽认证系统管理员  
RHCE(Red Hat Certified Engineer):红帽认证工程师
RHCVA:
RHCA(Red Hat Certified Architect):红帽认证架构师  
RHSCC:
<h4>Linux相关职位</h4>
Linux 运维工程师  
Linux系统集成工程师  
Linux系统架构师  
网站运维工程师  
数据库DBA  
ERP系统管理工程师

#Red Hat 安装
<h4>Vmware安装</h4>
<h5>认证序列号</h5>
VMware Workstation 12序列号: 5A02H-AU243-TZJ49-GTC7K-3C61N  
<h5>基础使用操作技巧</h5>
增加虚拟机可用的物理内存   
硬件设备添加的技巧  
控制器的切换技巧  
```
Ctrl+Alt
Ctrl+C 
Ctrl+L 清屏
```
正确开关机技巧  
结束任务的技巧  
`Ctrl+Alt+Ins` 等于 `Ctrl+Alt+Delete`  
显示模式切换的技巧  
网络使用的技巧  
虚拟机BIOS设置技巧   
`开机按F2`  
解决屏幕分辨率的技巧  
使用ISO光盘文件的技巧  
删除虚拟机的技巧  
快照管理技巧  

#组装一台服务器
1U服务器详细参数
```
华硕主板Z8NA-D6C  *1  ¥1850
Intel CPU E5620  *2  ¥2170*2=4340
希捷1TB ST31000524NS企业硬盘/SATA/32M/3年 *2  ¥1350*2=2700
现代DDR3 1333 ECC REG 8G服务器内存 ¥480*2=960
华南工控1U机箱 320元
全汉FSP400-601UG 400W 1U服务器电源 80PLUS认证1U电源  *1  ¥530
捷豹1U775涡轮风扇  ¥100*2=200
合计¥10900
优惠价 ¥10800
```
#RHEL 基本命令
<h4>Linux终端介绍</h4>
`tty`控制台终端 `pts`虚拟终端
<h5>图形界面之间的相互切换`tty1-tty6`</h5>
`tty1`图形界面,切换到字符界面终端命令:`Ctrl`+`Shift`+`Alt`+`F2-6`
字符切换回图形界面`Alt`+`F1`
<h5>`pts`虚拟终端</h5>
即为常见的shell命令操作控制界面
<h4>Shell提示符</h4>
<h4>Bash Shell基本语法</h4>
<h4>基本命令的使用:ls、pwd、cd</h4>
<h4>查看系统和BIOS硬件时间</h4>
<h4>Linux关机命令:shutdow、halt等</h4>
<h4>Linux7个启动级别</h4>
<h4>创建一个方便快捷实验环境快照</h4>
<h4>设置服务器在来电后自动开机</h4>