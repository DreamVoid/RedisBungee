# RedisBungee

RedisBungee为[Redis](http://redis.io)和BungeeCord搭建了一座桥梁。部署在[The Chunk](http://thechunk.net)以确保多Bungee服务端的配置顺利进行

## 编译

RedisBungee作为一个[maven](http://maven.apache.org)项目。您可以编译并将其安装到您的Maven本地存储库中：

    git clone https://github.com/minecrafter/RedisBungee.git
    cd RedisBungee
    mvn clean install

## 配置

**REDISBUNGEE需要一个REDIS服务器**，两个服务器之间的延迟越低越好（最好在同一本地服务器上）。 默认[配置](https://github.com/DreamVoid/RedisBungee/blob/master/src/main/resources/example_config.yml)会在插件第一次启动后保存
