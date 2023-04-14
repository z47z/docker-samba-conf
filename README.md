# 测试协议：cifs

# 拉取镜像
docker pull joebiellik/samba-server

# 启动
docker-compose up

# wingfuzz中参数填写

主机名：0.0.0.0
端口：445
共享文件夹用户名：joe
共享文件夹密码：samba