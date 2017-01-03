##一、初识 Hadoop2.x
1. Hadoop的发展前景， 实际应用
2. Hadoop2.x 概述（common, hdfs, yarn, mapreduce）
3. HDFS架构， YARN架构， MapReduce如何运行在YARN上讲解
4. Hadoop2.x 生态系统常用框架介绍
5. Hadoop2.x 环境搭建准备
6. 环境搭建配置之单机模式（单节点， HDFS， YARN）
7. 环境搭建配置之单机模式（历史服务器， YARN日志聚集）
8. Hadoop 2.x 两类配置文件， HDFS垃圾回收配置
9. Hadoop 2.x 3种启动方式， SSH无密码登录
10. Hadoop 2.x 各个服务器组件如何配置在那台服务器运行并测试（启动所有的节点）
11. Hadoop 2.x 本地编译讲解

##二、深入 Hadoop2.x
1. HDFS 架构讲解
2. HDFS交互式Shell使用
3. linux 下Hadoop2.x  Java开发环境配置
4. HDFS java API 之FileSystem
5. HDFS java API  之文件获取
6. HDFS java API  之文件上传
7. NameNode 启动详解（第一次， 第N+1次）
8. SecondaryNameNode 详解
9. HDFS safemode讲解及如何进入safemode（手动）
10. YARN发展及架构功能详解
11. YARN集群资源管理，调度， 节点资源配置
12. YARN生态系统， Slider讲解， flink
13. MapReduce 编程模型讲解
14. 编程WordCount程序，job编写
15. 编程WordCount程序分析后的具体实现
16. WordCount程序打包测试
17. job流程更改成模板
18. 回顾WordCount程序执行流程
19. MapReduce框架中数据类型讲解
20. 优化MapReduce编程模板
21. MapReduce执行流程Shuffle讲解
22. MapReduce执行流程Shuffle在代码中的体现
23. MapReduce在实际应用中常见优化

##三、高级 Hadoop2.x
1. Hadoop 2.x 分布式部署讲解
2. 分布式安装环境准备（虚拟机克隆， mac地址重新生成）
3. 主机名， IP地址设置
4. 基于Hadoop 2.x 伪分布式进行修改配置文件
5. 配置机器SSH无密码登录
6. 分布式部署之分发，测试， 监控
7. 分布式部署之环境问题和集群基准测试讲解
8. 使用ntp配置内网机器机器时间同步
9. 分布式协作框架Zookeeper架构功能讲解及本地模式安装部署
10. 分布式协作服务Zookeeper分布式安装部署
11. 回顾HDFS架构存在单节点故障及引出HDFS HA
12. HDFS HA架构设计及4大要点
13. 依据官方Reference讲解配置HDFS HA
14. 启动HDFS HA各守护进程
15. 对HDFS HA进行测试及引出自动故障转移
16. 使用Zookeeper对HDFS HA配置自动故障转移及测试
17. HDFS 2.x高级特性讲解
18. YARN HA架构及RM与NM Restart讲解
