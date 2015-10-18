Raft
----

***Intention***

Implement another copy of Raft algorithm in Go, which uses protobuf as data format and gRPC as RPC framework.

***Prerequisite***

[Introduction to Raft](https://raft.github.io/)  
[gRPC](http://www.grpc.io/)  
[ProtoBuf](https://github.com/gogo/protobuf)

**TODOs**

1. UAT based on more complex scenarios
2. Log Compaction
3. Log Snapshot
4. API Interfaces for upper layer service

***Acknowledgements***

[An introduction to Raft (CoreOS Fest 2015](https://www.youtube.com/watch?v=6bBggO6KN_k)  
[Raft implementation in etcd](https://github.com/coreos/etcd/tree/master/raft)
