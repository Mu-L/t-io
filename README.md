
# 网络编程很苦，用t-io后会很甜
t-io是基于Java开发的一款高性能网络编程框架。t-io强大的并发处理能力、高稳定性使其成为广大企业开发工程项目和应用的首选；t-io简单易学，专为解决网络编程痛点而生，使其被众多新老开发者所喜爱

[![Stargazers over time](https://whnb.wang/stars/tywo45/t-io)](https://whnb.wang/stars/tywo45/t-io)

# 源代码仓库
[![t-io gitee](https://www.tiocloud.com/2/imgs/product/tio/mayun.png) ](https://gitee.com/tywo45/t-io)
[![t-io github](https://www.tiocloud.com/2/imgs/product/tio/Github.png) ](https://github.com/tywo45/t-io)


# 为什么要开发t-io
与其坐学厚厚的《xxx权威指南》，不如站着自主研发，创造更多人一眼就懂的编程API

# t-io的前世今生
1. 2010年，t-io的原创作者talent-tan在某通讯大厂接手网管系统的通讯模块，老代码采用的是传统IO，一个client需要有3个线程来守，经常内存溢出和宕机。talent-tan临危受命，重写了通讯模块。随即萌生了构思一套新框架的想法，专门解决网络编程痛点
2. 2012年，经过两年的琢磨，基于nio写了talent-nio
3. 2013年，用talent-nio写了mycat中的一个透传模块
4. 2014年，用talent-nio实现了热波直播的IM模块
5. 2015年，talent-tan开始关注aio技术，同时把talent-nio中的线程池、锁处理、并发数据结构进行了进一步抽象
5. 2015年，开始关注aio技术，同时把talent-nio中的线程池、锁处理、并发数据结构进行了进一步抽象
6. 2016年，基于aio技术重写了talent-nio，命名为talent-aio，代码入驻码云，正式开源
7. 2017年，talent-aio更名为t-io，同年t-io成为GVP项目，t-io收获大量用户
8. 2018年，基于t-io实现了tio-http-server、tio-websocket-server、tio-webpack等周边产品
9. 2019年，华为某测试团队对基于t-io的某智慧产品进行了长达3~6个月的拷机极限压测，t-io经受住考验，为正式进入华为开源优选库做了扎实的铺垫
10. 2020年，t-io正式入驻华为开源优选库，t-io官网注册人数破万，基于t-io开发的第一款商业IM谭聊正式上市，集群版t-io也正式完成研发并通过压测
11. 2021年，客户反馈基于t-io研发的谭聊非常稳定

# t-io解决的痛点
t-io的出发点是解决网络编程的用户痛点，其使命是让天下再也没有难开发的网络程序，且看t-io给用户带来的惊喜
1. 易学易用，talent-tan之所以创造t-io，就是因为市面上同类产品学习成本大，所以在设计api时，特别关切用户的接受度。t-io第一批用户仅仅是看了t-io官方提供的示范工程就掌握了t-io
2. 全方位的数据监控能力：org.tio.core.stat.ChannelStat
3. 内置心跳超时检查、心跳定时发送能力
4. 极致打磨的底层集群能力，可无缝解决IM、物联网等大型产品的集群需求
5. 掉线自动重连能力
6. t-io实测性能一：1.9G内存稳定支持30万TCP长连接：https://www.tiocloud.com/61
7. t-io实测性能二：用t-io跑出每秒1051万条聊天消息：https://www.tiocloud.com/41
8. t-io实测性能三：netty和t-io对比测试结果：https://www.tiocloud.com/154
9. 内置ack消息能力
10. 内置半包粘包处理
11. 自创同步锁、同步安全线程池、同步数据结构等工具库，为业务应用提供丰富的开箱即用API
12. 内置慢攻击防御机制，帮助应用自动拉黑嫌疑IP
13. 丰富的生态，目前已经用t-io实现了http、websocket、mqtt及大量私有协议
14. 对开发工程师要求低，为企业节约人工成本
15. 性能卓越，为企业节约硬件部署成本

# t-io文档
https://www.tiocloud.com/doc/tio/85

# t-io技术白皮书
[《t-io技术白皮书》](https://www.tiocloud.com/tio.pdf)

[![t-io技术白皮书](https://images.gitee.com/uploads/images/2021/1123/155602_fde63447_355738.jpeg "t-io技术白皮书.jpg")](https://www.tiocloud.com/tio.pdf)


# t-io口碑

![t-io用户口碑(一)](https://res.tiocloud.com/202111/blog/upload/img/50/8931/1119484/88097537/74541310905/47/165441/1465242802995732480_sm.jpeg "t-io用户口碑1.jpg")

![t-io用户口碑(二)](https://res.tiocloud.com/202111/blog/upload/img/50/8931/1119484/88097537/74541310905/30/165441/1465242803872342016_sm.jpeg "t-io用户口碑2.jpg")

![t-io用户口碑(三)](https://res.tiocloud.com/202111/blog/upload/img/50/8931/1119484/88097537/74541310905/20/165442/1465242804337909760_sm.jpeg "t-io用户口碑3.jpg")

![t-io用户口碑(四)](https://res.tiocloud.com/202111/blog/upload/img/50/8931/1119484/88097537/74541310905/90/165441/1465242803121561600_sm.jpeg "t-io用户口碑4.jpg")

![t-io用户口碑(五)](https://res.tiocloud.com/202111/blog/upload/img/50/8931/1119484/88097537/74541310905/29/165441/1465242803469688832_sm.jpeg "t-io用户口碑5.jpg")

![t-io用户口碑(六)](https://res.tiocloud.com/202111/blog/upload/img/50/8931/1119484/88097537/74541310905/41/165441/1465242802333032448_sm.jpeg "t-io用户口碑6.jpg")

# t-io使用案例
[![t-io使用案例](https://images.gitee.com/uploads/images/2021/1123/155431_8a7ea725_355738.jpeg "t-io使用案例.jpg")](https://www.tiocloud.com/2/case/index.html)

# t-io见证历史
![t-io见证历史](https://images.gitee.com/uploads/images/2021/1123/155507_3cff18d2_355738.jpeg "t-io见证历史.jpg")

