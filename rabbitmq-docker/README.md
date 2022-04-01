# docker创建rabbitmq3.9服务

> 内置 `rabbitmq_delayed_message_exchange` 延迟队列插件


2.1.启动
以下所有命令在 docker-compose.yml 所在目录下执行。

```
$docker-compose up -d
```
2.2.停止
```
$docker-compose stop
```
2.3.重启
```
$docker-compose restart
```
2.4.docker-compose 命令帮助
```
$docker-compose help
```

Web 管控台访问
http://localhost:15672

账号:root

密码:123456

账号与密码可在 docker-compose.yml 配置文件找到并可自行配置。

端口号说明：

5672：用于 amqp 协议通信，用于程序连接 rabbitmq 使用。

15672：用于 rabbitmq 的 web 管控台访问端口。