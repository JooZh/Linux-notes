## Screen 使用

#### 创建 screen 会话

screen -S  name   创建screen会话，自定义screen虚拟终端的名称，name可以改为你想要的名称

```
[root@localhost ~]# screen -S name
```

#### 保存 screen 会话

按键盘上面的Ctrl+a，然后再按 d  保存当前的screen会话，返回主界面

#### 查看所有的screen 会话

```
[root@localhost ~]# screen -ls
```

#### 退出screen 会话

在某个screen会话中

```
[root@localhost ~]# exit
```

#### 删除 screen 会话

在主界面中 name 表示会话名称

```
[root@localhost ~]# screen -wipe name
```



