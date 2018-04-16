
## Spark
#### Spark机器学习--运用逻辑回归分析银行营销数据
> 存款营销是银行吸收存款的主要经营模式，通过现有数据建立模型来判断客户是否订阅存款业务，从而帮助商业银行更好的分配人力资源，提高业务量，以满足现阶段营销活动对提高营销成功率的期望。 本实验会使用spark机器学习中的逻辑回归算法，分析银行营销数据，按照机器学习开发步骤，建立逻辑回归模型，预测客户是否会存款，并评估预测模型的精确度。
- 实验1  运用逻辑回归分析银行营销数据
知识点: 1.Spark机器学习开发的常规步骤 2.Spark框架提供的特征转换算法StringIndex 3.Spark框架提供的特征转换算法OneHotEncoder 4.Spark提供的API对预测结果准确度进行评估 5.SparkSQL在Spark机器学习中的用法

#### Kmeans聚类算法评估足球比赛
> K-means 算法是集简单和经典于一身的基于距离的聚类算法，采用距离作为相似性的评价指标，即认为两个对象的距离越近，其相似度就越大。本节课主要讲解 K-means 算法，并给出个聚类足球比赛案例。
- 实验1  Kmeans 聚类算法评估足球比赛
知识点: 1.Scala基础编程 2.SparkMlib的Kmeans算法应用

#### 使用决策树算法预测森林植被
> 决策树（decision tree）——是一种被广泛使用的分类算法。相比贝叶斯算法，决策树的优势在于构造过程不需要任何领域知识或参数设置，在实际应用中，对于探测式的知识发现，决策树更加适用。
- 实验1  决策树算法用于预测森林植被
知识点: 1.Scala基础编程 2.向量机 3.SparkMlib的LabeledPoint的算法应用

#### Spark 机器学习之电影推荐系统
> MLlib 是运行在 Spark 上一个机器学习算法库，借助 Spark 的内存计算，可以使机器学习的模型计算时间大大缩短。本节课基于协同过滤算法实现简易电影推荐。
- 实验1  机器学习实现电影推荐系统

#### 使用 Spark 进行流量日志分析
> 日志在计算机系统中是一个非常广泛的概念，任何程序都有可能输出日志：操作系统内核、各种应用服务器等等。日志包含很多有用的信息，例如访问者的 IP、访问的时间、访问的目标网页、来源的地址以及访问者所使用的客户端的 UserAgent 信息等，分析日志能帮助企业营销做出决策，本节课将介绍如何用 Spark 分析日志。
- 实验1  Spark 流量分析日志
知识点: 1.二次排序 2.序列化 3.SparkRDD

#### Spark 实现黑名单实时过滤
> 本节课主要介绍 Spark 的算子，通过演示黑名单实时过滤案例来加深您对 Spark RDD 的理解， 适合刚有 Spark 基础 的人学习。
- 实验1  Spark 实现黑名单实时过滤
知识点: 1.nc 2.SparkStreaming 3.SparkRDD

#### 流式实时日志分析系统——《Spark 最佳实践》
> 我们知道网站用户访问流量是不间断的，基于网站的访问日志，即 Web log 分析是典型的流式实时计算应用场景。比如百度统计，它可以做流量分析、来源分析、网站分析、转化分析。另外还有特定场景分析，比如安全分析，用来识别 CC 攻击、 SQL 注入分析、脱库等。在本课程中，我们将基于 Spark Streaming 流式计算框架，简单地实现一个类似于百度分析的系统。本课程源自图灵教育的《Spark 最佳实践》第6章第3节，感谢图灵教育授权实验楼发布。
-  实验1  流式分析系统实现  
知识点: 1.Python模拟生成Nginx日志 2.SparkStreaming编程 3.服务器访问日志分析方法

#### Spark2.x 快速入门教程
> Spark进入2.0时代，引入了很多优秀特性，性能上有较大提升，API更易用。在“编程统一”方面非常惊艳，实现了离线计算和流计算API的统一，实现了Spark sql和Hive Sql操作API的统一。真正做到了“更简单、更快速、更智能”！
- 实验1  Spark2.x 新特性
知识点: 1.对标准的SQL支持 2.DataFrame和DatasetAPI介绍 3.StructuredStreaming
- 实验2  Spark SQL
知识点: 1.Dataframe/Dataset介绍 2.SparkSession 3.Dataframe/Dataset案例操作
- 实验3  Hive on Spark
知识点: 1.Hive/MySQL安装 2.Hive整合Spark 3.SparkSQL测试
- 实验4  Structured Streaming
知识点: 1.StructuredStreaming 2.outputmode
- 实验5  Spark 处理多种数据源
知识点: 1.Parquet数据源 2.Json数据源 3.JDBC数据源
- 实验6   Streaming 整合 Flume
知识点: 1.Flumeagent 2.SparkStreaming
- 实验7  Streaming 整合 Kafka
知识点: 1.KafkaReceiver 2.KafkaDirect 3.SparkStreaming 4.Maven

#### Spark的模式挖掘—FPGrowth算法
> 模式挖掘也叫关联规则，其实就是从大量的数据中挖掘出比较有用的数据，挖掘频繁项。比如说超市有大量的购物数据，从而可以根据用户的购物数据找到哪些商品之间关联性比较大。进行关联推销产品。也可以进行用户推荐。
- 实验1  Spark的模式挖掘—FPGrowth算法
知识点: 1.Scala基础编程 2.RDD的基本操作。Transformation和Actions 3.SparkMlib的FPGrowth的算法应用

#### Spark 自定义 UDF 分析 Uber 数据
> 在本课程中，你将了解如何利用 SQL Context 及相关的 API 进行统计分析。最后将通过一个Spark自定义 UDF 分析 Uber的实例，进一步学习如何利用 Spark SQL 分析数据。本课程难度为一般，属于初级级别课程，适合具有 Spark 基础的用户，学习 Spark SQL 的基础知识。
- 实验1  自定义 UDF 分析 Uber 数据
知识点: 1.SQLContext 2.自定义UDF函数 3.SQL语句

#### Spark 大数据动手实验
> 15个实验带你亲身体验Spark大数据分析的魅力，最快的上手教程，最新的技术领域，最多的动手实践。课程已全部上线，加入即可开始学习。
- 实验1  Spark 简介与安装（免费）  
- 实验2  Spark RDD与编程模型
- 实验3  Scala 编程快速教程
- 实验4  Spark 开发入门项目
- 实验5  Spark 分析Apache日志
- 实验6  Spark Streaming 实战项目
- 实验7  Spark SQL 实战项目
- 实验8  MLlib 实战项目
- 实验9  GraphX实战项目
- 实验10  IndexedRDD实战项目
- 实验11  SparkR 实战项目
- 实验12  Tachyon 实战项目
- 实验13  KeystoneML 实战项目
- 实验14  BlinkDB & Succinct 实战项目
- 实验15  Spark 综合项目

#### Spark流式计算电商商品关注度
> 本课程将使用Scoket来模拟用户浏览商品产生实时数据，数据包括用户当前浏览的商品以及浏览商品的次数和停留时间和是否收藏该商品。使用Spark Streaming构建实时数据处理系统，来计算当前电商平台最受人们关注的商品是哪些。适合有一定的Java编程基础以及一定得Spark知识，了解Streaming的工作机制的同学学习。
- 实验1  基于Spark实时计算商品关注度
知识点: 1.JavaScoket编程的基本原理 2.SparkStreaming应用的基本实现 3.DStream的基本操作 4.updateStateByKey的使用

#### Spark 基础之 DataFrame 高阶应用技巧
> 本课程将通过更加深入的讲解，使用真实的 SFPD 数据集，结合实际问题的分析过程，带你学习 DataFrame 的创建方式、常用操作、UDF 自定义函数 和重分区相关知识。
- 实验1  DataFrame详解
知识点: 1.DataFrame概念复习 2.创建DataFrame的两种方式 3.常用DataFrame操作 4.自定义函数 5.DataFrame的重分区

#### Spark 基础之 Streaming 快速上手
> Spark Streaming 是 Spark 引擎的一种扩展，适用于实时处理流式数据。本课程将带你学习 Spark Streaming 的工作机制，了解 Streaming 应用的基本结构，以及如何在 Streaming 应用中附加 SQL 查询。本课程难度为一般，属于初级级别课程，适合具有 Spark 基础的用户，熟悉 Spark Streaming 的工作机制。
- 实验1  Streaming 入门
知识点: 1.SparkStreaming的工作机制 2.Streaming应用的基本结构 3.DStream的概念和结构 4.如何在Streaming上运行SQL查询

#### Spark 基础之使用机器学习库 MLlib
> 在本课程中，你将可以学习到 Spark 的机器学习库—— MLlib 的相关知识，了解 MLlib 与 ML 之间的区别和联系，掌握 MLlib 中的几个基本数据类型。同时，本课程还将通过一个电影推荐的实例，讲解如何利用机器学习算法解决实际问题。本课程难度为一般，属于初级级别课程，适合具有 Spark 基础的用户，熟悉 Spark 平台中的机器学习库的基本使用方法。
- 实验1  MLlib 入门
知识点: 1.MLlib的基本概念 2.MLlib库的主要内容 3.MLlib的数据类型和算法种类 4.协同过滤算法 5.SparkSQL应用（复习）

#### Spark 基础之 DataFrame 基本概念学习
> 本课程将针对飞行准点率数据集，通过一些简单的分析任务来学习 DataFrame 的由来、构建方式以及一些常用操作。在本课程中，你可以了解到 Spark 生态体系中，核心的 RDD 与 DataFrame 之间的区别和联系。同时，你还可以学习到在 Spark 中加载数据集的方式、如何配置和使用第三方库等等。
- 实验1   DataFrame 基本概念学习
知识点: 1.DataFrame的基本概念 2.DataFrame的构建方式 3.DataFrame的基本操作 4.在Spark中加载第三方库

#### Spark基础之GraphX图计算框架学习
> 本课程将学习Spark体系中用于解决图和并行图计算问题的新组件——GraphX。GraphX通过RDD的扩展，在其中引入了一个新的图抽象，即顶点和边带有特性的有向多重图，提供了一些基本运算符和优化了的Pregel API，来支持图计算。在本课程中你将可以学习到GraphX 框架的基本使用技巧、属性图的定义和操作符的种类，以及PageRank 、连通分量和三角形计数这三个经典的图计算算法。
- 实验1  初识GraphX
知识点: 1.GraphX框架的使用 2.属性图的定义 3.GraphX操作符的种类 4.属性操作符 5.结构操作符 6.关联操作 7.近邻点聚合 8.缓存和清除缓存
- 实验2  GraphX 常用图算法练习
知识点: 1.PageRank算法 2.连通分量算法 3.三角形计数算法

#### Spark 基础之 SparkR 快速上手
> 本课程将学习 Spark 平台中对于 R 语言的支持前端——SparkR。课程将会讲解到如何在 SparkR 中创建和操作 DataFrame、如何运行 SQL 查询，以及如何利用机器学习相关的 API。最后还会通过一些简单的实例来学习如何在 SparkR 中进行时间序列分析。
- 实验1  SparkR 入门
知识点: 1.SparkR中的DataFrame创建 2.SparkR中的常用DataFrame操作 3.在SparkR上运行SQL查询 4.在SparkR上实现机器学习 5.在SparkR中实现时间序列分析

#### Spark 基础之 SQL 快速上手
> 在本课程中，你将可以学习到 Spark SQL 的基础概念，了解如何利用 SQL Context 及相关的 API 进行统计分析。最后还将通过一个分析股票价格与石油价格关系的实例，进一步学习如何利用 Spark SQL 分析数据。本课程难度为一般，属于初级级别课程，适合具有 Spark 基础的用户，学习 Spark SQL 的基础知识。
- 实验1  Spark SQL 入门
知识点: 1.SQL基本概念 2.SQLContext的生成和使用 3.16版本新API：Datasets 4.常用SparkSQL数学和统计函数 5.SQL语句 6.SparkDataFrame文件保存
