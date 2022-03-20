1. jar运行：
参考官方文档：https://github.com/alibaba/Sentinel/wiki/控制台
2. docker运行（开发模式推荐）：
拉取镜像：docker pull bladex/sentinel-dashboard
运行镜像：docker run --name sentinel -d -p 8858:8858 -d bladex/sentinel-dashboard
3. 访问地址
dashboard 地址：http://localhost:8858 (默认端口为8080)
账号密码都为：sentinel
Sentinel界面

参考
https://www.kancloud.cn/smallchill/blade/1289446
