## Zabbix 

### doc 
���zabbix�ĵ����ְ����������ֲᡢ����ʹ���ĵ������ü�ر����ĵ���  
��������...

### source
���������ü����롣`item_conf` �ļ��д��zabbix��ؽ��̵������ļ���
��֧�ּ�صĽ������£�  
| ���� | ���� |  �ļ��� |
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
��webҳ�����ü�ؼ�����#Guitar-Scores
