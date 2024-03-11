# chatserver
可以工作在nginx tcp负载均衡环境中的集群聊天服务器和客户端源码  基于muduo实现
# 编译方式
#### cd build/
#### rm -rf ./*
#### cmake ..
#### make
# 依赖环境
#### muduo网络库
#### nginx-1.12.1 --with-stream(手动编译) 用于TCP负载均衡
#### redis
#### mysql
#### json
