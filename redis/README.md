# docker创建redis 6.2服务

> 默认关闭持久化，若需要关闭请修改 redis.conf 的 appendonly 配置
> 默认开启密码访问，密码为123456，实际使用请修改 redis.conf 的 requirepass 配置


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

