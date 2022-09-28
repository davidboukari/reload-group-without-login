# reload-group-without-login

* https://superuser.com/questions/272061/reload-a-linux-users-group-assignments-without-logging-out

```
usermod -aG root ubuntu

$ exec su -l $USER

$ id
uid=1000(ubuntu) gid=1000(ubuntu) groups=1000(ubuntu),0(root),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),116(lxd)


```
