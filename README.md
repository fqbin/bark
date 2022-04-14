1.安装bark服务端，下载可执行文件:
https://github.com/Finb/bark-server/releases
或自己编译
https://github.com/Finb/bark-server

2.赋予权限

```
chmod +x bark-server_linux_amd64
```

3.运行

```
./bark-server_linux_amd64 -addr 0.0.0.0:8080 -data ./bark-data
```

4.请注意 bark-server 默认使用 /data 目录保存数据，请确保 bark-server 有权限读写 /data 目录，或者你可以使用 `-data` 选项指定一个目录

5.测试是否正常

```
Plain  Textcurl http://0.0.0.0:8080/ping
```

6.解析域名到服务器，添加站点并反向IP

7.bark-App添加私有服务器

