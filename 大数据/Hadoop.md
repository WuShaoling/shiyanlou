## Hadoop

#### MapReduce分析Youtube数据
> 本节课主要介绍了 Hadoop 开发环境搭建，并基于YouTube 数据集根据任务需求编写 MR 程序，然后讲解演示了直接运行与打 jar 运行的区别等，希望学完本节课，能帮助您理解并学会搭建 Hadoop 开发环境并编写 MR ，很快上手。
- 实验1  MapReduce 分析 Youtube 数据
知识点: 1.eclipse的Hadoop开发环境搭建 2.编写MR程序 3.本地运行 4.生成Jar包提交yarn运行（远程运行）

#### 使用flume收集数据
> Flume 可以从多个数据源获取数据，把这些数据传给远程主机（可能是一对多或流水线模型 中的多个目标），再把它们传给多个目的端。尽管 Flume 提供了开发自定义数据源和数据目的端的编程 API，但它原本就支持许多常见的场景。本课程源自图灵教育的《Hadoop基础教程》第10章，感谢图灵教育授权实验楼发布。
- 实验1  使用 Flume 收集数据  
知识点: 1.Flume核心概念agent 2.agent里面包含3个核心组件：source、channel、sink。 3.sink组件是用于把数据发送到目的地的组件，目的地包括hdfs、logger、avro、thrift、ipc、file、null、hbase、solr、自定义。


#### Hadoop 图处理--《hadoop应用框架》
> 对于图处理，hadoop的mapreduce提供一层合并，这表明我们不得不像剥洋葱一样来处理图数据，Giraph 是 Google Pregel 的一种开源实现。本课程将基于hadoop平台实现Giraph 分布式系统中的图处理。本课程源自图灵教育的《hadoop应用框架》第5章，感谢图灵教育授权实验楼发布。
- 实验1  Hadoop 图处理  
知识点: 1.Hadoop文件存储 2.块同步并行模型 3.Giraph 4.Maven编译jar

#### Hadoop 分布式文件系统——导入和导出数据
> 一个经典的数据架构中，Hadoop 是处理复杂数据流的核心。数据往往是从许多分散的系统中收集而来，并导入 Hadoop 分布式文件系统（HDFS）中，通过 MapReduce 或者其他基于MapReduce 封装的语言（如 Hive、Pig 和 Cascading 等）进行处理，将这些已经过滤、转换和聚合过的结果导出到一个或多个外部系统中。本章的重点将关注 HDFS 数据的导入与导出，主要内容包含与本地文件系统、关系数据库、NoSQL 数据库、分布式数据库以及其他 Hadoop 集群之间数据的互相导入导出。
- 实验1  Hadoop分布式文件系统——导入和导出数据  
知识点: 1.使用Hadoopshell命令导入和导出数据到HDFS 2.Pig脚本来演示下getmerge命令的功能 3.使用distcp实现集群间数据复制 4.使用Sqoop从MySQL数据库导入数据到HDFS 5.使用Sqoop从HDFS导出数据到MySQL

#### Hadoop入门进阶课程
> 课程涵盖了大数据领域常见的组件，如Hadoop，Mapreduce，HBase，Mahout，Pig，Hive，Sqoop等。首先从理论上进行介绍，然后让您在实验环境中一步步搭建，及相应的案例学习。学习完本课程您将对大数据有深入的了解，并能够很快的上手。
- 实验1  Hadoop介绍及1.X伪分布式安装  
- 实验3  MapReduce原理及操作
- 实验4  MapReduce应用案例
- 实验5  Pig介绍、安装与应用案例
- 实验6  Hive介绍和安装部署
- 实验7  Mahout介绍、安装与应用案例
- 实验8  HBase介绍、安装与应用案例
- 实验9  Sqoop介绍、安装与操作
- 实验10  Flume介绍与安装
- 实验11  Chukwa介绍与安装部署
- 实验12  Hadoop2.X 64位编译
- 实验13  Hadoop2.X 64位环境搭建

#### Hadoop部署及管理
> Hadoop是一款支持数据密集型分布式应用并以Apache 2.0许可协议发布的开源软件框架，本实验学习并实践Hadoop系统的不同模式的部署，以及基本的系统使用与管理。
- 实验1  Hadoop课程介绍  
知识点: 1.了解hadoop的概念 2.hadoop的使用场景
- 实验2  Hadoop单机模式安装
知识点: 1.下载解压/环境变量配置 2.Linux/shell 3.测试WordCount程序
- 实验3  Hadoop伪分布模式配置部署
知识点: 1.hadoop核心配置文件 2.文件系统的格式化 3.测试WordCount程序

#### 基于 Hadoop 对武侠小说进行词频分析
> 本课程是 Hadoop 的一个非常基础的应用项目，利用实验楼提供的 Hadoop 环境，对一本武侠小说的文集进行简单的 WordCount 词频统计，从而得到该书中出现频次最高的人名。需要一定的 Hadoop 和 MapReduce 基础。本课程难度为简单，属于入门级别课程，适合对 Hadoop 刚刚入门的用户，甚至没有接触过 Hadoop 的用户也可以按照步骤一步步做出来。
- 实验1  武侠小说词频统计
知识点: 1.熟悉Hadoop程序开发及执行流程 2.熟悉MapReduce基本原理 3.学习结巴分词用法 4.学习词频统计方法
