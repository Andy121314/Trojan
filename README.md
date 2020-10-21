一键脚本代码
此脚本感谢  atrandys

Github 项目地址：点击访问

波仔在 atrandys 的基础之上，合成了 4 IN 1 的一个 BBRPLUS 加速脚本，方便大家使用

First, update your system with apt-get update && apt-get dist-upgrade and reboot. This is optional, but recommended.

安装好 curl，若是有此环境，请跳过

apt-get update -y && apt-get install curl -y    ##Ubuntu/Debian 系统安装 Curl 方法
yum update -y && yum install curl -y            ##Centos 系统安装 Curl 方法
有些 VPS 需要安装 XZ 压缩工具

apt-get install xz-utils   #Debian/Ubuntu 安装 XZ 压缩工具命令
yum install xz    #CentOS 安装 XZ 压缩工具
Trojan 一键脚本代码：

bash <(curl -s -L https://github.com/V2RaySSR/Trojan/raw/master/Trojan.sh)
