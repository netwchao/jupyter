# 如何远程连接服务器

[远程连接服务器.pptx](https://github.com/netwchao/jupyter/files/7531224/8.pandas_2020.11.10.1.pptx)
下载linux 子程序B，去连接A和C

ssh wangchao@192.168.10.83  -L127.0.0.1:8080:192.168.10.83:1234

* 如果端口被占用，查看是哪个程序占用端口， 杀死该程序，再运行。

lsof -i:1234   
kill -9  PID

jupyter notebook

# jupyter notebook 后台运行

screen -S jupyter notebook
screen -R jupyter notebook
退出虚拟屏幕  Ctrl + A +D
