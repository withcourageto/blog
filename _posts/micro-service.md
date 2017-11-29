## 微服务技术栈(java)


### 1 基础知识：
* Java 基础
	- Java 并发
	- Java 多线程
	- RxJava(反应式编程)

* spring
	- spring boot
	- spring 4

* 数据库
	- mysql优化
* http
	- http协议
	- Restful 
* TCP/IP
	- TCP/IP 协议理解
	- scoket 编程
		* BIO 使用及原理
		* NIO 使用及原理
		* AIO 使用及原理

* Linux
	- Linux基础命令


### 2 核心技术

* 进程间通信(服务调用)
	- REST (*)
		* 服务端使用 Spring MVC
		* 客户端使用 Jersey
	- RPC 
	- 定制
		* netty
    - 消息队列(*)
		* RabbitMQ(*)
		* Kafka(*)
		* Zero MQ
		* Apache ActiveMQ
	
* 服务注册与发现
	- spring cloud (*)
	- dubbo
	- motan
	- netflix oss

* 负载均衡
	- 服务端
		* Nginx (*)
		* HA proxy
		* LVS
		* Apache
	- 客户端
		* Ribbon (*)

* 熔断
	- Hystrix (*)

* 网关
	- Zuul(*)

### 3 基础设施
* 分布式配置管理
	- disconf (*)
	- diamond 
	- spring cloud config (*)
* APM 应用性能监控

* 服务监控
	- Hystrix Dashboard (*)
	- Metrics
	- Zabbix
	- Turbine
	
* 日志分析
	- Elasticsearch + Logstash + Kibana (*)
	- Prometheus + Grafana
* 服务跟踪
	- Zipkin 
	- spring cloud sleuth

### 4 其他重要
* 全局控制
	- leader选举
	- 分布式锁
	- 全局唯一Id
* 服务部署
	- docker
 



