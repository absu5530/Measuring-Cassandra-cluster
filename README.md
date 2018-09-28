# Measuring Cassandra cluster
Measured the latencies and clock skew of Cassandra database clusters set up in Docker containers on AWS platforms, for different topologies (with nodes set up in varying locations)

In performing reads or writes on Cassandra nodes, there is a latency in propagating these reads and writes to all the nodes of the cluster. There is also a clock offset among nodes of the same cluster even if they communicate with the same NTP server to synchronize their clocks. The degree of latencies and offset was studied across different cluster topologies.
