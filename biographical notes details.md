  <center> <h1>王佳铭</h1><div>
     <span>
         <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/phone-solid.svg" width="18px">
         13233610897
     </span>
     ·
     <span>
         <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/envelope-solid.svg" width="18px">
         792836909@qq.com OR 792836909qq@gmail.com
     </span>
      <br>
     ·
     <span>
         <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/github-brands.svg" width="18px">
         <a href="https://github.com/Jmwang-Code">Jmwang-Code</a>
     </span>
     ·
     <span>
         <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/rss-solid.svg" width="18px">
         <a href="https://blog.csdn.net/jj89929665?type=blog">My Blog</a>
     </span>
 </div> </center>

## <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/info-circle-solid.svg" width="30px"> 个人信息

- 男 26岁
- 求职意向：Java 研发工程师 、Java 大数据工程师
- 工作经验：3 年
- 期望薪资：22-25k



## <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/graduation-cap-solid.svg" width="30px"> 教育经历

- 学士，山西农业大学，软件工程专业，17级
- 绩点：3.8，年级前 20%
- 通过了 CET4 英语等级考试



## <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/briefcase-solid.svg" width="30px"> 工作经历

- **南京万得资讯科技有限公司，基础大数据 部门、商业大数据 部门、风控大数据 部门，Java 研发工程师**

  **2020.9~2022.8**

  主要负责：

      1. 数据收集、数据治理、数据加工、数据品控。

      2. 业务沉淀共性抽离为指导思想，独立开发公共服务 “Validation” 、“Label”、“Monitor”（校验、标签、监控）。设计、研发、维护。

      3. 算法服务:独立完成-实体识别树的设计、研发、维护。


- **北京擎创科技有限公司，北区共研开发部，后端开发工程师、大数据开发工程师**

  **2022.8~至今**

  主要负责：

      1. 独立开发-数据报表项目的核心数据源提供者的设计、研发、维护。

      2. Flink算子开发、以及Aviator数据接入处理、Pull-Nebula数据入ck、Flink-CDC数据迁移。
  
  

## <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/project-diagram-solid.svg" width="30px"> 项目经历

- **实体识别树**

  *Springboot Sqlite Redis ElasticSearch JDBC SpringCloud Nacos Feign*

1. [ ] 参与流程：架构设计、详细设计、编码实现、单元测试、部署上线、维护。
2. [ ] 解决问题：补全了在公司人工智能部实体识别树之外的实体识别树，NPL训练的模型识别目的性强，受算力和模型影响识别较慢，在大数据的场景下需要更快的检索速度。
3. [ ] 使用方法：核心使用算法树，使得项目的检索速度达到1ms级别,时间复杂度在公司场景下常数，并且使用“荷官”服务同步数据,(预备多套方案保证数据问题CA,外部机制保证P)。

- **数据报表**

  *Springboot Redis ElasticSearch JDBC H2*

1. [ ] 参与流程：架构设计、详细设计、编码实现、单元测试、部署上线、维护。
2. [ ] 解决问题：解决了数据报表的展示数据问题，数据源的数据量大，数据源的数据结构复杂，数据源的数据格式类型多样,通过高扩展的设计将多种优势数据源接入并且统一展示类型，聚合计算、以及对应数据源特性计算。
3. [ ] 使用方法：使用了我的<span style="color:grey;">[Data-Provider](https://github.com/Jmwang-Code/Data-Provider)**开源项目**</span>的设计原稿，将数据源的数据格式类型转换为统一的展示类型。

- **中台数据调度**

  *Flink Aviator Nebula Flink-CDC Flink-Sql*

1. [ ] 参与流程：详细设计、编码实现、单元测试。
2. [ ] 解决问题：解决了数据调度的问题，数据源的数据量大，数据源的数据结构复杂，数据源的数据格式类型多样,通过高扩展的设计将多种优势数据源接入并且统一展示类型，聚合计算、以及对应数据源特性计算。
3. [ ] 使用方法：使用Nebula图数据量进行多CMDB数据表之间关联进行CK入库，使用Flink-CDC进行数据迁移，使用Aviator进行数据拆分和聚合、FlinkSql进行数据丰富。




## <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/github-brands.svg" width="30px"> 个人开源

| \   | 开源项目名称                                                                             | 依赖类型 | 版本号            | 描述                                                            |
|-----|------------------------------------------------------------------------------------|------|----------------|-----------|
| 1   | [spring-boot-starter-trie](https://github.com/Jmwang-Code/spring-boot-starter-trie) | pom  | 1.0.0-SNAPSHOT | 特定需求下查询速度远超开源检索工具，innodb下B+树或者ES中倒排索引无法与之比拟.                       |
| 2   | [spring-boot-starter-trie](https://github.com/Jmwang-Code/spring-boot-trie-service) | jar  | 1.0.0-M1       | 提供了基于SpringCloud的服务节点，可以通过Nacos注册中心进行服务发现，实现了树的动态扩容与缩容，以及服务的动态上下线。 |
| 3   | [Data-Provider](https://github.com/Jmwang-Code/Data-Provider) | pom  | 1.0.0-SNAPSHOT | 提供了多种数据源的查询，以及数据的类型同步，作为一个Jar可以依赖在其他服务上动态的提供数据。               |
| 4   | [EasyExcel](https://github.com/alibaba/easyexcel) | pom  | 3.3.1          | alibaba开源项目，基于POI的Excel工具，可以实现大数据量的Excel导入导出，加入开源团队。 |

- [CSDN (595 articles)](https://blog.csdn.net/jj89929665)
- [Github (700+ submissions、Over 10000 lines of code) ](https://github.com/Jmwang-code)

## <img src="https://raw.githubusercontent.com/Jmwang-Code/Jmwang-Code/main/assets/icon/tools-solid.svg" width="30px"> 技能清单


**语言**
- ★★★ Java CGLIB和JDK、集合、Synchronized、ReentrantLock、SPI、线程池、等
- ★☆☆ Aviator 已经快速上手
- ★☆☆ goland 可以快速学习上手
- ★☆☆ Python 可以快速学习上手
- ★☆☆ JavaScript 可以快速学习上手

**框架**
- ★★★ Spring 核心原理、IOC、AOP、transaction、Bean
- ★★☆ SpringBoot 使用
- ★☆☆ SpringCloud 基本使用（Nacos、Feign、Gateway、Hystrix）

**数据库**
- ★★☆ MySQL InnoDB引擎原理、索引原理、锁原理、事务原理、SQL优化理解、SQL执行计划、主从原理、复制协议
- ★☆☆ ClickHouse 列式存储、数据分区、数据索引、数据缓存、数据分布式计算

**中间件**
- ★★☆ Redis 数据结构、分布式锁、缓存穿透、缓存击穿、缓存雪崩、哨兵模式
- ★☆☆ ElasticSearch 倒排索引、跳表
- ★☆☆ Kafka 数据丢失、重复消费、消费顺序性、生产精确性

**大数据体系**
- ★★☆ Hadoop 核心原理（HDFS、MapReduce、Yarn）
- ★★☆ Spark Spark核心原理、RDD原理、Spark离线计算
- ★★☆ Flink Flink核心原理、Flink实时计算               CDC数据迁移、Pull-Nebula数据入ck