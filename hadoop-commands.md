### Hadoop Commands

|Sl.No.| Commands                   | Description                       |
|------|----------------------------|-----------------------------------|
| 01.   |hdfs namenode -format       |                                   |
| 02.   |C:\Hadoop\hadoop.2.7.1\sbin> start-all.cmd | It will start Namenode, Datanode, YARN resourcemanager, YARN nodemanager process |
| 03.   |start-dfs.cmd        |                              |
| 04.   |start-yarn.cmd       |                              |
| 05.   |jps 				 |  to see services are running |
| 06.   |hdfs dfs -cat <src>  |                              |
| 07.   |hdfs dfs -ls         |                              |
| 08.   |hdfs dfs             |                              |
| 09.   |dfs                  |run a filesystem command on the file systems supported in Hadoop.|
| 10.   |namenode -format     |format the DFS filesystem|
| 11.   |secondarynamenode    |run the DFS secondary namenode|
| 12.   |namenode             |run the DFS namenode|
| 13.   |journalnode          |run the DFS journalnode|
| 14.   |zkfc                 |run the ZK Failover Controller daemon|
| 15.   |datanode             |run a DFS datanode|
| 16.   |dfsadmin             |run a DFS admin client|
| 17.   |haadmin              |run a DFS HA admin client|
| 18.   |fsck                 |run a DFS filesystem checking utility|
| 19.   |balancer             |run a cluster balancing utility|
| 20.   |jmxget               |get JMX exported values from NameNode or DataNode.|
| 21.   |oiv                  |apply the offline fsimage viewer to an fsimage|
| 22.   |oev                  |apply the offline edits viewer to an edits file|
| 23.   |fetchdt              |fetch a delegation token from the NameNode|
| 24.   |getconf              |get config values from configuration|
| 25.   |groups               |get the groups which users belong to|
| 26.   |snapshotDiff         |diff two snapshots of a directory or diff current directory contents with a snapshot|
| 27.   |lsSnapshottableDir   |list all snapshottable dirs owned by the current user|
| 28.   |cacheadmin           |configure the HDFS cache|
| 29.   |mover                |run a utility to move block replicas across storage types|
| 30.   |storagepolicies      |list/get/set block storage policies |
| 31.   |start-all.sh         |Starts all Hadoop daemons, the namenode, datanodes, the jobtracker and tasktrackers.|
| 32.   |stop-all.sh          |Stops all Hadoop daemons.|
| 33.   |start-mapred.sh      |Starts the Hadoop Map/Reduce daemons, the jobtracker and tasktrackers.|
| 34.   |stop-mapred.sh       |Stops the Hadoop Map/Reduce daemons.|
| 35.   |start-dfs.sh         |Starts the Hadoop DFS daemons, the namenode and datanodes.|
| 36.   |stop-dfs.sh          |Stops the Hadoop DFS daemons.|