### 问题记录
- Exception in thread "main" org.apache.hadoop.ipc.RemoteException: Server IPC version 9 cannot communicate with client version 4

pom.xml文件中不能仅仅指定hadoop core（最高版本是1.2.1），
还需要指定hadoop common ,hadoop client,hadoop hdfs
就根本不用hadoop core