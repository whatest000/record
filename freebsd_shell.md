### **ssh配置**

```
vi /etc/ssh/sshd_config

主要修改以下两个地方
PermitRootLogin yes
PasswordAuthentication yes
AllowUsers root

执行
/etc/rc.d/sshd restart
```

### **修改系统时间**

```
ntpdate time.windows.com
date
```
