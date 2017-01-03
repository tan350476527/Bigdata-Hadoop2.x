一、初识 Hadoop2.x
01Hadoop的发展前景， 实际应用
02Hadoop2.x 概述（common, hdfs, yarn, mapreduce）
03HDFS架构， YARN架构， MapReduce如何运行在YARN上讲解
04Hadoop2.x 生态系统常用框架介绍
05Hadoop2.x 环境搭建准备
06环境搭建配置之单机模式（单节点， HDFS， YARN）
07环境搭建配置之单机模式（历史服务器， YARN日志聚集）
08Hadoop 2.x 两类配置文件， HDFS垃圾回收配置
09Hadoop 2.x 3种启动方式， SSH无密码登录
10Hadoop 2.x 各个服务器组件如何配置在那台服务器运行并测试（启动所有的节点）
11Hadoop 2.x 本地编译讲解

二、深入 Hadoop2.x
01HDFS 架构讲解
02HDFS交互式Shell使用
03linux 下Hadoop2.x  Java开发环境配置
04HDFS java API 之FileSystem
05HDFS java API  之文件获取
06HDFS java API  之文件上传
07NameNode 启动详解（第一次， 第N+1次）
08SecondaryNameNode 详解
09HDFS safemode讲解及如何进入safemode（手动）
10YARN发展及架构功能详解
11YARN集群资源管理，调度， 节点资源配置
12YARN生态系统， Slider讲解， flink
13MapReduce 编程模型讲解
14编程WordCount程序，job编写
15编程WordCount程序分析后的具体实现
16WordCount程序打包测试
17job流程更改成模板
18回顾WordCount程序执行流程
19MapReduce框架中数据类型讲解
20优化MapReduce编程模板
21MapReduce执行流程Shuffle讲解
22MapReduce执行流程Shuffle在代码中的体现
23 MapReduce在实际应用中常见优化

三、高级 Hadoop2.x
01Hadoop 2.x 分布式部署讲解
02分布式安装环境准备（虚拟机克隆， mac地址重新生成）
03主机名， IP地址设置
04基于Hadoop 2.x 伪分布式进行修改配置文件
05配置机器SSH无密码登录
06分布式部署之分发，测试， 监控
07分布式部署之环境问题和集群基准测试讲解
08使用ntp配置内网机器机器时间同步
09分布式协作框架Zookeeper架构功能讲解及本地模式安装部署
10分布式协作服务Zookeeper分布式安装部署
11回顾HDFS架构存在单节点故障及引出HDFS HA
12HDFS HA架构设计及4大要点
13依据官方Reference讲解配置HDFS HA
14启动HDFS HA各守护进程
15对HDFS HA进行测试及引出自动故障转移
16使用Zookeeper对HDFS HA配置自动故障转移及测试
17HDFS 2.x高级特性讲解
18YARN HA架构及RM与NM Restart讲解
