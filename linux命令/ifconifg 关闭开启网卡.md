# ifconifg 关闭开启网卡

---

## 命令格式

`ifconfig [网络设备] [参数]`

## 参数

* `up` 启动指定网络设备或网卡.
* `down` 关闭指定网络设备/网卡. 可以有效地阻止通过指定接口的IP信息流, 如果想永久地关闭一个接口, 还需要从核心路由表中将该接口的路由信息全部删除.