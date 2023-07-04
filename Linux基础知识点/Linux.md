## 时间 ⏱ 

```
查看时间
date -R

查看时区
timedatectl

修改时间
1.修改年月日 =>将系统日期设置为2023年7月4日
date -s 2023-07-04

2.修改时间
date -s 17:21:00  =>将系统时间设置为下午5点21

3.同时修改年月日与时间
date -s "2023-07-04 17:21:00"

4.注意无论是修改了时间还是修改了日期最后都需要将时间写入Bios
hwclock -w

修改时区:复制时区文件夹下对应的（时区文件📂），替换（系统时区文件📂）
cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
```

