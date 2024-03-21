# aboutMe
 个人简介

# 个人信息

 - moyu
 - 本科/ 软件工程 
 - 工作年限：6年
 - 技术博客：https://blog.csdn.net/apawnchuck_129?type=blog
 - 期望职位：Java高级程序员，数据开发,应用架构师
 - 期望薪资：面议
 - 期望城市：深圳,广州,东莞

# 联系方式

- 手机：****
- Email：**@163.com
- 微信号：**

# 技能清单
以下均为我熟练使用的技能
- 数据采集：Flume/Sqoop/Python
- 消息队列: Kafka/RabbitMQ
- ETL框架：Kettle/DataX/Canal/Maxwell/Otter
- 大数据云产品：MaxCompute/EMR/MRS/DLF/Databricks/DLI/DLC
- 大数据云产品: Oozie/Azkaban/DolphinScheduler/CDH6/Atlas/Grafana/Promethus/Apache Ranger/Sentry
- 数据分析： Hadoop/Hive/SparkSQL/Impala/Spark/Flink
- 数据库相关：Oracle/MySQL/TiDB/OceanBase/Mongo/PgSQL/Hbase/Phoenix/Redis/TDengine/Elasticsearch/Clickhouse/Doris/Hudi/Druid/Kylin/Superset
- 版本管理、文档和自动化部署工具：Svn/Git
- 报表组件： FineBI/FineReport/QuickBI
- 编程语言: Python/Java/Scala/Golang
- Linux相关: Docker/K8s/jekins/Zabbix/
- 前端框架: HTML/CSS/JavaScript/HTML5/Ajax/Json/XML/React/Vue/Typescript/Node.js/MVVM 框架/NodeJS/Webpack/RollUp
-  后端框架：Spring/Springmvc/Springboot/MyBatis/MQ/Springcloud
/Dubbo/Zookeeper


# 工作经历


## XX公司

### XX项目 
该项目项目使用 Spark 技术，结合 Kafka、Hive、Hbase、Phoenix 等大数据组件，完成业务数据的实时 ETL 开发、Hive 离线数仓开发、Phoenix 整合 Hbase 完成即席查询 模块开发以及 SparkSQL离线 OLAP 分析。通过对生产物料、产品产量、良率、产品缺陷类型比率和设备运行状况等指标的监控，有利于节约物料成本、在生产过程中及时调整生产，提高品良，指导设备维护。
1. Phoenix 整合 Hbase，在 Phoenix 可视化页面使用 Sql 进行即席查询进行即席查询模块开发；
2. 使用 SparkSql 在 Hbase 中进行机台产量、员工产量、订单追踪、机台预警、产品量、良率缺陷类型占比和设备稼动等指标的实时 OLAP 分析。
3. 基于 flink cdc 完成业务数据到 Kafka 的对接，实现维度数据到 phoenix 的配置化开发。
4. 基于 flink 实现机台数百个参数的业务数据清洗，并为后续机台告警业务提供服务。
5. 基于 flink 实现班产对比、工艺参数对比、机台产量对比、停机告警等模块的实时计算任务。
6. 完成了低延迟、高可用、易扩展的代码开发，同时成为了公司的模板代码，并在其他项目中优化和迭代
7. 参与 Flink 实时业务数据处理工作，优化实时业务相关代码，提高运行效率
业绩：
1、取得业绩
（1）实现公司多业务支持与产品落地。
（2）实现公司基础服务的改造与升级。
2、实现突破
（1）助力公司纺织工业互联网项目落地与投产。
（2）实现公司敏捷化之路。

### 基础数据中台项目 
使用技术：Spring Cloud Alibaba + Gateway + Nacos + RocketMQ + Vue & Element
纺织终端数据接口服务是一种针对纺织行业设计的实时数据采集与分析解决方案，它通过标准化的数据接口，无缝对接各类生产现场设备和信息系统，实现对纺织生产全流程关键指标的实时监控和深度洞察。
具体功能包括：
物料成本管理：系统实时收集并分析生产物料的使用情况，包括物料消耗量、损耗率等数据，通过精细化管理和预测性分析，帮助企业优化物料采购策略及生产流程，从而有效节约物料成本。
产量与效率监控：实时追踪产品产量数据，结合生产设备运行状态信息，能够快速识别生产瓶颈，合理调配资源，提升整体生产线的运转效率。
产品质量控制：通过对产品良率的实时统计分析，以及对不同缺陷类型的比率监测，可以及时发现质量问题源头，采取针对性的质量改进措施，稳步提高产品品质。
设备维护预警：通过集成设备传感器数据，实时监测设备运行状况，如故障率、工作效率、保养周期等，提前预判潜在故障风险，指导企业进行预防性维护，减少因设备停机带来的生产损失。
1.负责项目整体设计包括以上全部模块，主导技术选型。保证服务各个环节的高可用。避免单点故障问题。
2.负责维护支撑100多万台物联网设备数据的搜索引擎，维护了7个节点的elasticsearch集群。
3.从零搭建elasticsearch集群，并解决集群安全通信，跨集群数据同步问题。通过双集群的设计，来保证服务高可用。通过心跳机制，来动态切换集群。解决了elasticsearch分布式搜索引擎的脑裂问题。通过副本和快照来保证数据不丢失。
4.负责elasticsearch搜索引擎的后续优化工作。在数据集从2亿增长到5亿，数据容量从2T到5T的情况下，通过对集群的升级及规划和索引合理拆分，将聚类检索的时间从10秒降低到了2秒、普通检索从5秒降到1秒以下。集群写入速度提升到了3w/s。
5.使用nginx作为流量网关，使用gateway+nacos+sentinel 搭建了业务网关。期间改造了sentinel源码，来支撑生产环境下，业务网关零停服情况下的动态修改限流规则的需求。通过改源码将sentinel规则持久化到nacos，实现限流规则从客户端到sentinel的dashbord再到nacos的闭环。对鉴权、限流、等公共能力进行了抽取。通过对公共能力的抽取，将网关下沉为公共服务，发挥组内技术优势，为研究所内其他开发小组提供网关技术支持。帮助其它组解决用户鉴权，限流，降级等问题。



## XX公司

### XX项目 
技术架构：Springboot、Springcloud、 Flume、Kafka、Flink,Azkban、 Echarts、 Zookeeper、 Nginx、
Sqoop、Hbase、Elasticsearch 等技术。
项目描述：
智慧里程可视化大屏一共分为续航里程、能耗分析、行程分析、驾驶行为分析等几个模块。通过计算分析开始 Soc、结束 Soc、开始里程、结束里程、行驶里程等分析，计算出车辆的能耗曲线，预测车辆的续航里程，并为售后服务部解决续航投诉提供数据支撑；结合采集到的加速度、转向盘角度、加速踏板开度等分析用户在不同场景、不同环境（行驶环境、起步习惯、怠速状况、加速行为等）下的车辆使用情况。结合行驶里程电量电耗曲线、温控制系统（Hvh）电耗曲线、空调系统（Ptc/Ac）电耗曲线、急加速（急减速）电虚曲线、Dc-Dc 温控曲线等要分析能量消耗情况，分析出最经济的驾驶方式
项目职责:
• 负责通过 Java 实现数据中台后端业务开发和单元测试，通过 Jenkins 和 Docker-Compose 进行项目部署
• 负责通过 Datax、Canal、Flume 同步业务数据到 Cdh 集群，定位数据库慢查询并优化读写速度,查询速度由原来的2.3s,优化到 0.1s,速度提升了近十倍.
• 负责设计开发数据埋点服务，实现用户行为埋点分析和数据可视化
• 负责采集 Impala 和 Hive 数据血缘日志推送到 Kafka，实时消费 Kafka 数据写入 Hbase，实现元数据的实时采集和数据血缘影响分析
• 负责 Cdh 大数据集群接入 Prometheus 监控，平均每天 1TB左右监控数据入库，实现对集群的监控预警和问题定位





### 智能运维平台项目
该产品是一个面向数据中心运维场景的Saas系统，目前已在广东省内联通所有合作机房和自有机房内使用。功能涵括数据中心日常运维场景，如日常巡检、作业计划、告警管理、能耗管理等。
个人责任：
· 负责核心模块开发，如数据采集模块、北向接口模块、分布式任务调度模块等。
· 负责业务模块开发，如巡检计划、作业计划、能耗管理等模块。
· 负责BUG修复及项目优化。
使用技术：
· 该项目基于spring cloud框架开发，使用nginx做反向代理，使用zuul做服务网关，业务服务基于spring boot开发。
· 使用Zipkin做链路跟踪，Hystrix做容错保护，Prometheus做监控。
· 使用Eureak做注册中心，Spring Cloud Config做集中配置管理。
· 使用Mysql数据库，Redis缓存层，RocketMQ作为消息队列，OpenTsdb作为时序数据库
· 定时任务框架使用Quartz，文件系统使用Fastdfs，实时通信使用WebSocket。




---      
# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。

