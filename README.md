# 1 需求分析：

（1）智能分析:用户输入目标、原始数据、图表类型，可以自动生成图表和分析结论

（2）图表管理

（3）图表生成的异步化(消息队列)：因为chatGPT生成时间比较慢，可能一个图表需要很长时间，如果很多用户同时使用，会影响并发量，导致服务器崩溃。

（4）对接AI能力

# 2 架构图：

![332698504-1eddd9b1-1ada-4145-a894-207470923aa0](https://github.com/swx2021/DataElf/assets/80183322/c93947cd-a454-4c04-b5d1-83d5ea0054ed)





# 3 技术栈：

（1）Spring Boot

（2）MySQL 数据库

（3）MyBatis Plus 数据访问框架

（4）消息队列(RabbitMQ)

（5）Al能力(Open AI接口开发)

（6）Excel的上传和数据的解析(Easy Excel)

（7）Swagger + Knife4j项目接口文档

（8）Hutool工具库

