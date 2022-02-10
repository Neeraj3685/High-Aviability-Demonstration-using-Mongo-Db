# High-Aviability-Demonstration-using-Mongo-Db


MongoDB has great support for high availability through ReplicaSets. However, deploying a ReplicaSet is not enough for a production-ready system. The latter requires a bit of planning. Deployment is just the initial step, we then need to arm the operational teams with monitoring, alerting, security, anomaly or failure detection, automatic recovery/failover, backup management, and other tools to keep the environment up and running.

redundancy and data high availability - multiple copies of data on different database servers offer a high level of fault tolerance against the data loss.

scalability and autodiscovery – new nodes, added during horizontal scaling, are connected to the cluster with all required adjustments being applied automatically.

automated failover – the database nodes that are temporarily unavailable or have high latency are automatically excluded from the cluster and re-added once the connection is restored.
