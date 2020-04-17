# pandownload-fake-server
https://www.hostloc.com/thread-675311-1-1.html

感谢 hostloc@xjxaixxy 大佬提供的思路与文件

感谢 [Womsxd/pandownload.com_Pages_Backup](https://github.com/Womsxd/pandownload.com_Pages_Backup) 的脚本文件
# 使用方法
1.打开你电脑的C:\Windows\System32\drivers\etc

2.hosts属性->只读取消勾选

3.hosts 添加
```
64.52.84.68 pandownload.com
```

目前看来bdc token和启动并无太大联系，理论上此方法将一直可用
# 想说的话
**F\*\*k Baidu**

＃ 可能的启动脚本

python -m http.server 80
127.0.0.1 pandownload.com
ipconfig /flushdns
