---
title: 同步时间
date: 2019-06-13 16:45:56
tags: ntpdate
---
#时间同步
ubuntu时间同步
apt-get install ntpdate -y
#VM
cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
centos:
yum install ntpdate -y
ntpdate -u ntp.api.bz
ntp常用服务器：
中国国家授时中心：210.72.145.44
NTP服务器(上海) ：ntp.api.bz
美国：time.nist.gov
复旦：ntp.fudan.edu.cn
微软公司授时主机(美国) ：time.windows.com
台警大授时中心(台湾)：asia.pool.ntp.org

