# 描述，包含服务
* php 7.0
* nginx
* redis 
* mysql 5.7
* composer

# 构建，不要被墙
* docker-compose build --no-cache
* docker-compose up

# 启动
* 如果本地已启动了Nginx，并且端口为80,则docker 启动时，Nginx不能为80， 目前是默认为81，本地访问通过nginx代理

