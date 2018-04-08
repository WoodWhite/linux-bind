# DNS
> DNS（Domain Name System）
[RFC1034](https://tools.ietf.org/html/rfc1034) [RFC1035](https://tools.ietf.org/html/rfc1035)

# DNS 开源软件
> [Bind](https://ftp.isc.org/isc/bind9/cur/9.11/doc/arm/Bv9ARM.html)、CoreDNS、PowerDNS、SmartDNS、Dnsmasq、DNSPod-SR、Atomia DNS 

# Bind
> Bind（Berkeley Internet Name Domain）

```
操作系统：Centos7
1. 安装
命令：yum install -y bind bind-chroot bind-utils

2. 配置

3. 检查
命令：named-checkconf /etc/named.conf 
     named-checkzone "test.com" /var/named/test.com.zone
     
4. 启动
命令：systemctl start named.service

5. 加载
命令：systemctl reload named.service
```



