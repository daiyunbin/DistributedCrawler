# 设计思路
> 本项目由 Node.js 开发。该框架主要适用高并发，但每次爬取数据量不大的分布式爬虫

用到的技术包括
* PM2 负责开启和监控应用；
* RabbitMQ 负责任务调度；
* Server 由 Express 编写