# auto_expansion
自动扩容阿里云ECS的脚本，支持与流程
1、多项目配置
2、选择最新系统盘、数据盘快照
3、通过上一步快照制作镜像
4、通过上一步镜像制作ECS
5、调取paramiko远程执行初始化shell脚本
6、request模块检查服务api
7、配置默认权重，自动加入指定的SLB负载均衡
