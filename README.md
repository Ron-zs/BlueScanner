这是一个开发中的蓝队扫描器脚本，能够便捷的进行挖矿排查、木马远控排查、敏感目录排查。

目标1：能够扫描持久化常见目录：etc/crontab、/etc/rc.local、/var/spool//etc/crontab、/usr/bin/crontab

目标2：能够通过微步或者Virtuals接口扫描排查所有的网络连接是否有害。

目标3：能够排查CPU占用率高的进程。

目标4：能够针对某一进程PID进行深入排查，包括守护进程、隐藏进程、进程文件、关联文件等。

目标5：能够针对某一文件进行深入排查，包括各种权限、同一时期创建的文件、相似名称的文件、相似大小的文件。

目标6：排查重点目录：./tmp 、./bin 、 /root/.ssh/ 、 /etc/resolv.conf、 /etc/init.d/和/etc/rc.d/init.d/
