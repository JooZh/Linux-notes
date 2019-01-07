## Nginx 使用

#### 从容停止

查看进程号

```
[root@LinuxServer ~]# ps -ef|grep nginx

root      3656     1  0 08:57 ?        00:00:00 nginx: master process nginx
nginx     3657  3656  0 08:57 ?        00:00:00 nginx: worker process
root      3695  2196  0 09:04 pts/0    00:00:00 grep --color=auto nginx
```

杀死进程

```
[root@LinuxServer ~]# kill -QUIT 3656
```

#### 重启

```
[root@LinuxServer ~]# nginx
```

