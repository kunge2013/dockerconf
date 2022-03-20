## 1.安装docker-compose
## 2.cd /user/local/docker/rocketmq/
## 3.mkdir data -- 在/user/local/docker/rocketmq/data下面
## 4.copy docker-compose.yml到/user/local/docker/rocketmq下面
## 5.mkdir  /user/local/docker/rocketmq/data/brokerconf/
## vi brokerconf.yml
copy 过去
## 6./usr/local/docker/rocketmq# docker-compose up -d
## 7.docker -ps
查看是否启动


## 8.参考文献
 参考
https://www.jianshu.com/p/706588323276


## 9.若提示 RocketmqRemoting: closeChannel: close the connection to remote address[] result: true可能是公网Ip没有配置，
那么需要在broker.conf中添加
... 
 conf/broker.conf
 ==
 brokerIP1=X.X.X.X（公网IP）
