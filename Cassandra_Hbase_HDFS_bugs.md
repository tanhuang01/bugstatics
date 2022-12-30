### bugs of "type conversion", "type casting", "type coercion" from Cassandra, HBase and HDFS. 

[link to the online search reasul](https://issues.apache.org/jira/issues/?jql=project%20in%20(CASSANDRA%2C%20HDFS%2C%20HBASE)%20AND%20issuetype%20%3D%20Bug%20AND%20text%20~%20%22%5C%22type%20coercion%5C%22%20OR%20%5C%22type%20conversion%5C%22%20OR%20%5C%22type%20casting%5C%22%22%20ORDER%20BY%20key%20ASC%2C%20issuetype%20DESC%2C%20summary%20ASC%2C%20cf%5B12310041%5D%20DESC)

|Issue_Type|Issue_key|Issue_id|Summary|Assignee|Reporter|Priority|Status|Resolution|Created|Updated|Due Date|
|----|----|----|----|----|----|----|----|----|----|----|----|
|Bug|[CASSANDRA-7809](https://issues.apache.org/jira/browse/CASSANDRA-7809)|12735784|UDF cleanups (#7395 follow-up)|slebresne|slebresne|Normal|Resolved|Fixed|21/Aug/14 13:52|16/Apr/19 09:31|
|Bug|[CASSANDRA-10027](https://issues.apache.org/jira/browse/CASSANDRA-10027)|12853695|ALTER TABLE TYPE check broken|blerer|aploetz|Low|Resolved|Fixed|09/Aug/15 15:20|16/Apr/19 09:31|
|Bug|[CASSANDRA-10311](https://issues.apache.org/jira/browse/CASSANDRA-10311)|12863679|AbstractType value compatibility checks are broken for some of the implementations||benedict|Normal|Resolved|Not A Problem|13/Sep/15 10:14|16/Apr/19 09:30|
|Bug|[CASSANDRA-11053](https://issues.apache.org/jira/browse/CASSANDRA-11053)|12932942|COPY FROM on large datasets: fix progress report and optimize performance part 4|stefania|stefania|Normal|Resolved|Fixed|21/Jan/16 01:56|16/Apr/19 09:30|
|Bug|[CASSANDRA-12417](https://issues.apache.org/jira/browse/CASSANDRA-12417)|12995894|Built-in AVG aggregate is much less useful than it should be|ifesdjeen|blambov|Normal|Resolved|Fixed|09/Aug/16 09:24|16/Apr/19 09:30|
|Bug|[HBASE-10499](https://issues.apache.org/jira/browse/HBASE-10499)|12694476|In write heavy scenario one of the regions does not get flushed causing RegionTooBusyException|yuzhihong@gmail.com|ram_krish|Critical|Closed|Fixed|11/Feb/14 12:00|06/Apr/18 17:55|
|Bug|[HBASE-19433](https://issues.apache.org/jira/browse/HBASE-19433)|13123031|ChangeSplitPolicyAction modifies an immutable HTableDescriptor|yuzhihong@gmail.com|elserj|Critical|Resolved|Fixed|05/Dec/17 23:14|01/Aug/18 06:22|
|Bug|[HBASE-18762](https://issues.apache.org/jira/browse/HBASE-18762)|13099968|Canary sink type cast error|ckulkarni|ckulkarni|Major|Resolved|Fixed|05/Sep/17 21:56|14/Dec/18 10:08|
|Bug|[HDFS-3673](https://issues.apache.org/jira/browse/HDFS-3673)|12599044|libhdfs: fix some compiler warnings|cmccabe|cmccabe|Minor|Closed|Fixed|16/Jul/12 21:20|11/Oct/12 17:46|
|Bug|[HDFS-15792](https://issues.apache.org/jira/browse/HDFS-15792)|13354825|ClasscastException while loading FSImage|prasad-acit|prasad-acit|Major|Resolved|Fixed|27/Jan/21 06:41|22/Mar/21 03:15|
|Bug|[HDFS-16044](https://issues.apache.org/jira/browse/HDFS-16044)|13380704|Fix getListing call getLocatedBlocks even source is a directory|pilchard|pilchard|Major|Patch Available||27/May/21 08:47|09/Jan/22 08:53|
