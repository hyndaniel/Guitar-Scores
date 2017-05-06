## Zabbix 

### doc 
存放zabbix文档，现包含：部署手册、基本使用文档、配置监控报警文档。  
持续更新...

### source
存放相关配置及代码。`item_conf` 文件夹存放zabbix监控进程的配置文件。
现支持监控的进程如下：  
| 服务 | 进程 |  文件名 |
| :--: | :--: | :--: |
| Hadoop | NameNode, SecondaryNameNode, DataNode, ResourceManager, NodeManager | check_hadoop_process |
| HBase | HMaster, HRegionServer | check_hbase_process |
| Hive | HiveServer2, MetaStore | check_hive_process |
| Kafka | Kafka | check_kafka_process |
| ElasticSearch | ElasticSearch | check_elasticsearch_process |
| Zookeeper | QuorumPeerMain | check_zookeeper_process |

#### How to install process item 
`cp item_conf/*.conf /etc/zabbix_agentd.d/`  
`service zabbix-agent restart`  
在web页面配置监控及报警#Guitar-Scores
